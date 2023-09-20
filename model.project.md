<!-- markdownlint-disable -->

# <kbd>module</kbd> `model.project`






---

## <kbd>class</kbd> `Project`




### <kbd>method</kbd> `__init__`

```python
__init__(configuration_file)
```








---

### <kbd>method</kbd> `get_config_value`

```python
get_config_value(file_type, section: str, key: str)
```

Get the value from the appropriate custom configuration file based on the provided file type. 



**Args:**
 
 - <b>`file_type`</b> (ConfigCustomFileType):  The type of configuration file to use (e.g., Code, Terms). 
 - <b>`section`</b> (str):  The section within the configuration file. 
 - <b>`key`</b> (str):  The key for the configuration value. 



**Returns:**
 
 - <b>`Any`</b>:  The configuration value found in the specified section and key, or None if the file is not available. 



**Raises:**
 
 - <b>`Warning`</b>:  If the specified key or section is not found in the configuration file. 


---

## <kbd>class</kbd> `ConfigCustomFileType`
An enumeration. 





