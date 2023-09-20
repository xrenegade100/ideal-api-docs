<!-- markdownlint-disable -->

# <kbd>module</kbd> `common.types_list`





---

## <kbd>function</kbd> `get_collection_types`

```python
get_collection_types(
    project: Project,
    language: LanguageType
) → Optional[List[str]]
```

Get collection data types for a specific programming language. 



**Args:**
 
 - <b>`project`</b> (Project):  The project instance containing project-specific configuration. 
 - <b>`language`</b> (LanguageType):  The programming language for which collection data types are requested. 



**Returns:**
 
 - <b>`List[str] or None`</b>:  A list of collection data types for the specified language, including custom types if defined in the project configuration,  or None if the language is not recognized. 


---

## <kbd>function</kbd> `get_primitive_types`

```python
get_primitive_types(language: LanguageType) → Optional[List[str]]
```

Get primitive data types for a specific programming language. 



**Args:**
 
 - <b>`language`</b> (LanguageType):  The programming language for which primitive data types are requested. 



**Returns:**
 
 - <b>`List[str] or None`</b>:  A list of primitive data types for the specified language,  or None if the language is not recognized. 


---

## <kbd>function</kbd> `get_numeric_types`

```python
get_numeric_types(language: LanguageType) → Optional[List[str]]
```

Get numeric data types for a specific programming language. 



**Args:**
 
 - <b>`language`</b> (LanguageType):  The programming language for which numeric data types are requested. 



**Returns:**
 
 - <b>`List[str] or None`</b>:  A list of numeric data types for the specified language,  or None if the language is not recognized. 


---

## <kbd>function</kbd> `get_bool_types`

```python
get_bool_types(language: LanguageType) → Optional[List[str]]
```

Get boolean data types for a specific programming language. 



**Args:**
 
 - <b>`language`</b> (LanguageType):  The programming language for which boolean data types are requested. 



**Returns:**
 
 - <b>`List[str] or None`</b>:  A list of boolean data types for the specified language,  or None if the language is not recognized. 


