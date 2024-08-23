# PYTHON TIPS & TRICS

## File operations

### Use `r` before the file path to indicate that it is a raw string, meaning that backslashes (`\`) are treated as literal characters and not as escape sequences.
Example:
```python
with open ( r'C:\Users\mzeml\python\python-tips-and-tricks\test.csv' , 'r' , encoding = 'utf-8' ) as file:
    file_content = file.read ()
