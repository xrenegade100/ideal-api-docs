<!-- markdownlint-disable -->

# <kbd>module</kbd> `service.parser`




**Global Variables**
---------------
- **PIPE**


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


---

## <kbd>class</kbd> `Structures`
An enumeration. 





---

## <kbd>class</kbd> `PythonParser`




### <kbd>method</kbd> `__init__`

```python
__init__(parsed_file)
```








---

### <kbd>method</kbd> `extract_attribute`

```python
extract_attribute()
```

Extracts variables and their comments from the target file by calling the private method `__extract()`. 

---

### <kbd>method</kbd> `extract_function`

```python
extract_function()
```

Extracts information about functions from the parsed code and adds them to the list of functions. 

---

### <kbd>method</kbd> `get_attributes`

```python
get_attributes() → Optional[List[GreetAttribute]]
```

Returns a list of GreetAttribute objects if there are attributes in the parsed file, otherwise None. 



**Returns:**
 
 - <b>`Optional[List[greet_attribute.GreetAttribute]]`</b>:  A list of GreetAttribute objects or None. 

---

### <kbd>method</kbd> `get_functions`

```python
get_functions() → Optional[List[GreetFunction]]
```

Returns a list of GreetFunction objects if there are functions in the parsed file, otherwise None. 



**Returns:**
 
 - <b>`Optional[List[greet_function.GreetFunction]]`</b>:  A list of GreetFunction objects or None. 

---

### <kbd>method</kbd> `parse_file`

```python
parse_file()
```

Parses the file by extracting attributes and functions. 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
