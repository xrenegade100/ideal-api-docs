<!-- markdownlint-disable -->

# <kbd>module</kbd> `common.testing_list`





---

## <kbd>function</kbd> `get_null_check_test_method`

```python
get_null_check_test_method(
    project: Project,
    language: LanguageType
) → Optional[List[Any]]
```

Get null check test methods for a specific programming language. 



**Args:**
 
 - <b>`project`</b> (Project):  The project for which null check test methods are retrieved. 
 - <b>`language`</b> (LanguageType):  The programming language for which null check test methods are requested. 



**Returns:**
 
 - <b>`Optional[List[Any]]`</b>:  A list of null check test methods for the specified language, or None if the language is not recognized. 


---

## <kbd>function</kbd> `get_testing_packages`

```python
get_testing_packages(
    project: Optional[Project],
    language: LanguageType
) → Optional[List[Any]]
```

Get testing packages for a specific programming language. 



**Args:**
 
 - <b>`project`</b> (Project):  The project for which testing packages are retrieved. If None, the function uses the default project from TestingPackage. 
 - <b>`language`</b> (LanguageType):  The programming language for which testing packages are requested. 



**Returns:**
 
 - <b>`Optional[List[Any]]`</b>:  A list of testing packages for the specified language,  or None if the language is not recognized. 


---

## <kbd>function</kbd> `get_test_method_annotations`

```python
get_test_method_annotations(
    project: Project,
    language: LanguageType
) → Optional[List[Any]]
```

Get test method annotations for a specific programming language. 



**Args:**
 
 - <b>`project`</b> (Project):  The project for which test method annotations are retrieved. 
 - <b>`language`</b> (LanguageType):  The programming language for which test method annotations are requested. 



**Returns:**
 
 - <b>`Optional[List[Any]]`</b>:  A list of test method annotations for the specified language,  or None if the language is not recognized. 


---

## <kbd>class</kbd> `TestingPackage`




### <kbd>method</kbd> `__init__`

```python
__init__()
```








---

### <kbd>method</kbd> `set_project`

```python
set_project(project: Project)
```






