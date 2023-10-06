<!-- markdownlint-disable -->

# <kbd>module</kbd> `common.util`





---

## <kbd>function</kbd> `get_config_setting`

```python
get_config_setting(section: str, name: str)
```

Retrieve a specific configuration value from a configuration file. 



**Args:**
 
 - <b>`section`</b> (str):  The name of the section in the configuration file. 
 - <b>`name`</b> (str):  The name of the configuration setting within the section. 



**Returns:**
 
 - <b>`str`</b>:  The requested configuration value. 


---

## <kbd>function</kbd> `get_file_name`

```python
get_file_name(file_path: str) → str
```

Extract the file name from a given file path. 



**Args:**
 
 - <b>`file_path`</b> (str):  The full path to the file, including its name. 



**Returns:**
 
 - <b>`str`</b>:  The file name extracted from the file path. 


---

## <kbd>function</kbd> `remove_list_nestings`

```python
remove_list_nestings(l: List[Any]) → List[Any]
```

Flatten a nested list, removing all levels of nesting. 



**Args:**
 
 - <b>`l`</b> (List[Any]):  The nested list to be flattened. 



**Returns:**
 
 - <b>`List[Any]`</b>:  A flat list with all elements from the input list. 


---

## <kbd>function</kbd> `get_supported_file_extensions`

```python
get_supported_file_extensions() → List[str]
```

Get a list of supported file extensions. 



**Returns:**
 
 - <b>`List[str]`</b>:  A list of supported file extensions. 


---

## <kbd>function</kbd> `read_input`

```python
read_input(path_string: str) → List[Any]
```

Read and process input data from a CSV file. 



**Args:**
 
 - <b>`path_string`</b> (str):  The path to the input CSV file. 



**Returns:**
 
 - <b>`List[Any]`</b>:  A list of Input objects, each representing a file and associated metadata. 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
