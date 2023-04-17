
# UserFiles

A simple module like configparser.


## Installation

    pip install UserFiles
    
## Usage/Examples

#### Simple Example:
```python
my_files = UserFiles('my_user_files.userfiles')
my_files['username'] = 'johndoe'
print(my_files['username'])  # Output: johndoe

del my_files['username']
print('username' in my_files)  # Output: False
```

## Documentation

## `__init__(self, filename)`
Constructor for the UserFiles class.
#### Arguments:
    • filename (str): The name of the .userfiles file to use.
---
---
---
---

## `__getitem__(self, section)`
Getter method for the UserFiles class. Retrieves a dictionary of key-value pairs for a given section.
#### Arguments:
    • section (str): The section of the .userfiles file to retrieve.

#### Returns:
    A dictionary of key-value pairs for the given section.
---
---
---
---
## `__setitem__(self, section, values)`
Setter method for the UserFiles class. Adds a dictionary of key-value pairs to a given section.
#### Arguments:
    • section (str): The section of the .userfiles file to add the key-value pairs to.
    • values (dict): A dictionary of key-value pairs to add to the specified section.
---
---
---
---
## `__contains__(self, section)`
Checks if a section exists in the .userfiles file.
#### Arguments:
    • section (str): The section of the .userfiles file to check for.

#### Returns:
    • True if the section exists in the .userfiles file, False otherwise.
---
---
---
---
## `__delitem__(self, section)`
Deletes a section and its key-value pairs from the .userfiles file.
#### Arguments:
    • section (str): The section of the .userfiles file to delete.
---
---
---
---
## `get_sections(self)`
Returns a list of all the sections in the .userfiles file.
#### Returns:
    • A list of all the sections in the .userfiles file.
---
---
---
---
## `get_options(self, section)`
Returns a list of all the options in a given section of the .userfiles file.
#### Arguments:
    • section (str): The section of the .userfiles file to retrieve the options from.
#### Returns:
    • A list of all the options in the given section of the .userfiles file.
---
---
---
---
## `get(self, section, option)`
Retrieves the value of an option in a given section of the .userfiles file.
#### Arguments:
    • section (str): The section of the .userfiles file to retrieve the option from.
    • option (str): The name of the option to retrieve.
#### Returns:
    • The value of the specified option in the specified section.
## License

[MIT](https://choosealicense.com/licenses/mit/)

