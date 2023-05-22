# Email Checker (Assignment 4)

Note: was having issues cloning the colab notebook to github so I will just add screenshots of the output here

```py
import re

email = input("'Ello, please enter your email address: ")

reggie = r'^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$'

if re.match(reggie, email):
    print("Valid email format")
else:
    print("Invalid email format")

```

### Valid email

![valid email output](https://i.imgur.com/M6rH0KA.png)

### Invalid email

![invalid email output](https://i.imgur.com/TlYKpYn.png)
