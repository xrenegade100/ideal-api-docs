<!-- markdownlint-disable -->

# <kbd>module</kbd> `service.factory`






---

## <kbd>class</kbd> `EntityFactory`
A factory class for constructing Entity objects from source code files. 

**Attributes:**
  None 

### <kbd>method</kbd> `__init__`

```python
__init__()
```








---

### <kbd>method</kbd> `construct_model`

```python
construct_model(source_path: str, file_type, junit: bool) → Optional[Entity]
```

Construct an Entity object from a source code file. 

**Args:**
 
 - <b>`source_path`</b> (str):  The path to the source code file. 
 - <b>`file_type`</b> (str):  The type of the source code file. 
 - <b>`junit`</b> (bool):  Whether the source code is related to JUnit testing. 

**Returns:**
 
 - <b>`Entity`</b>:  The constructed Entity object. 

**Note:**

> VSCode complains about types because of `Entity`'s constructor setting all attributes to None, and it is useless since that is standard Python behavior. 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
