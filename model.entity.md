<!-- markdownlint-disable -->

# <kbd>module</kbd> `model.entity`






---

## <kbd>class</kbd> `Entity`




### <kbd>method</kbd> `__init__`

```python
__init__()
```








---

### <kbd>method</kbd> `construct_hierarchy`

```python
construct_hierarchy()
```





---

### <kbd>method</kbd> `is_using_testing_package`

```python
is_using_testing_package(source: _ElementTree) → None
```

Determine if the source is using testing packages and set the file type accordingly. 



**Args:**
 
 - <b>`source`</b> (etree._ElementTree):  The source code represented as an ElementTree. 



**Returns:**
 
 - <b>`None`</b>:  This function modifies the `self.file_type` attribute based on the analysis. 

---

### <kbd>method</kbd> `set_file_type`

```python
set_file_type(file_type)
```

Set the file type. 



**Args:**
 
 - <b>`file_type`</b> (Union[int, FileType]):  The file type to set 
        - If `file_type` is 1, the file type will be set to FileType.Test. 
        - If `file_type` is 2, the file type will be set to FileType.NonTest. 
        - Otherwise, the file type will be set to FileType.Unknown. 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
