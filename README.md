# Python Projects: Password Generator
Python Script <br>
This repo contains python code that generates a random password' <br>
Run the code.

Python
```python
import random
import string

total = string.ascii_letters + string.digits + string.punctuation

length = 16

password = "".join(random.sample(total, length))

print(password)
```

Output
```python
^:eD6l,sQm`Zkg;T
```

