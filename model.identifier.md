<!-- markdownlint-disable -->

# <kbd>module</kbd> `model.identifier`




**Global Variables**
---------------
- **SRCML_LINE_COL_NUMS_XPATH**


---

## <kbd>class</kbd> `Class`
Represents a class in the source code. 

### <kbd>method</kbd> `__init__`

```python
__init__(name: str, source)
```

Initialize a Class object. 



**Args:**
 
 - <b>`name`</b> (str):  The name of the class. 
 - <b>`source`</b>:  The source code for the class. 




---

### <kbd>method</kbd> `set_block_comment`

```python
set_block_comment(comment: Optional[str])
```

Set the block comment for the class. 



**Args:**
 
 - <b>`comment`</b> (str):  The block comment for the class. 


---

## <kbd>class</kbd> `Attribute`
Represents an attribute within a class. 

### <kbd>method</kbd> `__init__`

```python
__init__(
    specifier,
    type,
    name,
    parent_name,
    is_array: bool,
    is_generic: bool,
    source
)
```

Initialize an Attribute object. 



**Args:**
 
 - <b>`specifier`</b>:  The attribute specifier (e.g., public, private). 
 - <b>`type`</b>:  The data type of the attribute. 
 - <b>`name`</b>:  The name of the attribute. 
 - <b>`parent_name`</b>:  The name of the parent class. 
 - <b>`is_array`</b> (bool):  Indicates if the attribute is an array. 
 - <b>`is_generic`</b> (bool):  Indicates if the attribute type is generic. 
 - <b>`source`</b>:  The source code for the attribute. 




---

### <kbd>method</kbd> `get_fully_qualified_name`

```python
get_fully_qualified_name() → str
```

Get the fully qualified name of the attribute, including the parent class. 



**Returns:**
 
 - <b>`str`</b>:  The fully qualified name. 

---

### <kbd>method</kbd> `set_block_comment`

```python
set_block_comment(comment)
```

Set the block comment for the attribute. 



**Args:**
 
 - <b>`comment`</b> (str):  The block comment for the attribute. 


---

## <kbd>class</kbd> `Property`
Represents a property within a class. 

### <kbd>method</kbd> `__init__`

```python
__init__(type, name, parent_name, is_array: bool, is_generic: bool, source)
```

Initialize a Property object. 



**Args:**
 
 - <b>`type`</b>:  The data type of the property. 
 - <b>`name`</b>:  The name of the property. 
 - <b>`parent_name`</b>:  The name of the parent class. 
 - <b>`is_array`</b> (bool):  Indicates if the property is an array. 
 - <b>`is_generic`</b> (bool):  Indicates if the property type is generic. 
 - <b>`source`</b>:  The source code for the property. 




---

### <kbd>method</kbd> `get_fully_qualified_name`

```python
get_fully_qualified_name() → str
```

Get the fully qualified name of the property, including the parent class. 



**Returns:**
 
 - <b>`str`</b>:  The fully qualified name. 

---

### <kbd>method</kbd> `set_block_comment`

```python
set_block_comment(comment: str)
```

Set the block comment for the property. 



**Args:**
 
 - <b>`comment`</b> (str):  The block comment for the property. 


---

## <kbd>class</kbd> `Method`
Represents a method within a class. 

### <kbd>method</kbd> `__init__`

```python
__init__(
    specifier,
    name,
    annotations,
    parent_name,
    return_type,
    is_array: bool,
    source
)
```

Initialize a Method object. 



**Args:**
 
 - <b>`specifier`</b>:  The method specifier (e.g., public, private). 
 - <b>`name`</b>:  The name of the method. 
 - <b>`annotations`</b>:  List of method annotations. 
 - <b>`parent_name`</b>:  The name of the parent class. 
 - <b>`return_type`</b>:  The return type of the method. 
 - <b>`is_array`</b> (bool):  Indicates if the return type is an array. 
 - <b>`source`</b>:  The source code for the method. 




---

### <kbd>method</kbd> `get_all_comments`

```python
get_all_comments(unique_terms=True) → List[str]
```

Get all comments associated with the method. 



**Args:**
 
 - <b>`unique_terms`</b> (bool):  Whether to return unique comment terms. 



**Returns:**
 
 - <b>`List[str]`</b>:  List of comments. 

---

### <kbd>method</kbd> `get_fully_qualified_name`

```python
get_fully_qualified_name() → str
```

Get the fully qualified name of the method, including the parent class. 



**Returns:**
 
 - <b>`str`</b>:  The fully qualified name. 

---

### <kbd>method</kbd> `get_inner_comments`

```python
get_inner_comments() → List[Any]
```

Get inner comments within the method. 



**Returns:**
 
 - <b>`Unknown`</b>:  List of inner comments. 

---

### <kbd>method</kbd> `get_parameters_as_string`

```python
get_parameters_as_string()
```

Get the method parameters as a string. 



**Returns:**
 
 - <b>`str`</b>:  A string representation of method parameters. 

---

### <kbd>method</kbd> `set_block_comment`

```python
set_block_comment(comment: Optional[str])
```

Set the block comment for the method. 



**Args:**
 
 - <b>`comment`</b> (str):  The block comment for the method. 


---

## <kbd>class</kbd> `Variable`
Represents a variable within a method. 

### <kbd>method</kbd> `__init__`

```python
__init__(specifier, type, name, is_array: bool, is_generic: bool, source)
```

Initialize a Variable object. 



**Args:**
 
 - <b>`specifier`</b>:  The variable specifier (e.g., public, private). 
 - <b>`type`</b>:  The data type of the variable. 
 - <b>`name`</b>:  The name of the variable. 
 - <b>`is_array`</b> (bool):  Indicates if the variable is an array. 
 - <b>`is_generic`</b> (bool):  Indicates if the variable type is generic. 
 - <b>`source`</b>:  The source code for the variable. 




---

### <kbd>method</kbd> `get_fully_qualified_name`

```python
get_fully_qualified_name() → str | None
```

Get the fully qualified name of the variable, including the parent method or class. 



**Returns:**
 
 - <b>`str`</b>:  The fully qualified name. 

---

### <kbd>method</kbd> `set_block_comment`

```python
set_block_comment(comment)
```

Set the block comment for the variable. 



**Args:**
 
 - <b>`comment`</b> (str):  The block comment for the variable. 

---

### <kbd>method</kbd> `set_parent_name`

```python
set_parent_name(parent_name: str)
```

Set the parent name (method or class) to which the variable belongs. 



**Args:**
 
 - <b>`parent_name`</b> (str):  The name of the parent method or class. 


---

## <kbd>class</kbd> `Parameter`
Represents a parameter passed to a method. 

### <kbd>method</kbd> `__init__`

```python
__init__(type, name, is_array: bool, is_generic: bool, source)
```








---

### <kbd>method</kbd> `get_fully_qualified_name`

```python
get_fully_qualified_name() → str | None
```

Get the fully qualified name of the parameter, including the parent method or class. 



**Returns:**
 
 - <b>`str`</b>:  The fully qualified name. 

---

### <kbd>method</kbd> `set_block_comment`

```python
set_block_comment(comment: str)
```

Set the block comment for the parameter. 



**Args:**
 
 - <b>`comment`</b> (str):  The block comment for the parameter. 

---

### <kbd>method</kbd> `set_parent_name`

```python
set_parent_name(parent_name: str)
```

Set the parent name (method or class) to which the parameter belongs. 



**Args:**
 
 - <b>`parent_name`</b> (str):  The name of the parent method or class. 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
