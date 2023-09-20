<!-- markdownlint-disable -->

# <kbd>module</kbd> `service.parser`




**Global Variables**
---------------
- **PIPE**
- **STDOUT**
- **DEVNULL**


---

## <kbd>class</kbd> `Parser`
A utility class for parsing source code files using srcML. 

**Attributes:**
 
 - <b>`parsed_string`</b> (str):  The parsed source code as a string. 

### <kbd>method</kbd> `__init__`

```python
__init__()
```








---

### <kbd>method</kbd> `parse_file`

```python
parse_file(file_path: str) → bool
```

Parse a source code file using srcML. 

**Args:**
 
 - <b>`file_path`</b> (str):  The path to the source code file. 

**Returns:**
 
 - <b>`bool`</b>:  True if parsing was successful, False otherwise. 


