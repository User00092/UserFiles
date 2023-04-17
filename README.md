
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
#### Arguments:
    filename (str): The name of the .userfiles file to use.

## `__getitem__(self, section)`
#### Arguments:
    section (str): The section of the .userfiles file to retrieve.


## License

[MIT](https://choosealicense.com/licenses/mit/)

