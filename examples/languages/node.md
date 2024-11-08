---
runme:
  id: 01JC6V65TAV0EXKYSS511GK09X
  version: v3
---

## Node

You can run Node code by setting the language of the cell to `Babel JavaScript`. To set the binary manually, click `Configure`, goto the `Advanced` tab and set the interpreter to whatever you want, `/usr/bin/nodejs` for example.

```python {"id":"01JC6RX7NJSEA7XPBPW78Z88BC","interpreter":"","name":"node-greeting"}
import datetime

# Define a variable for the greeting
greeting = "Hello, World!"

# Get the current date and time
currentDateTime = datetime.datetime.now().strftime('%Y-%m-%d %H:%M:%S')

# Concatenate the greeting with the current date and time
fullGreeting = greeting + " It's now " + currentDateTime

# Output the full greeting
print(fullGreeting)
```
