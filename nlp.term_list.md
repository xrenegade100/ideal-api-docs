<!-- markdownlint-disable -->

# <kbd>module</kbd> `nlp.term_list`




**Global Variables**
---------------
- **splitter_terms**
- **pos_terms**
- **plural_terms**
- **transform_terms_staring**
- **transform_terms_inner**
- **conditional_terms**
- **validate_terms**
- **boolean_terms**
- **get_terms**
- **set_terms**

---

## <kbd>function</kbd> `get_splitter_terms`

```python
get_splitter_terms(project: Project) → List[str]
```

Get the splitter terms for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve splitter terms. 



**Returns:**
 
 - <b>`list`</b>:  A list of splitter terms. 


---

## <kbd>function</kbd> `get_pos_terms`

```python
get_pos_terms(project: Project) → Dict[str, str]
```

Get the part-of-speech (POS) terms for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve POS terms. 



**Returns:**
 
 - <b>`dict`</b>:  A dictionary of POS terms where keys are terms, and values are their POS labels. 


---

## <kbd>function</kbd> `get_plural_terms`

```python
get_plural_terms(project: Project) → List[str]
```

Get plural terms for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve plural terms. 



**Returns:**
 
 - <b>`list`</b>:  A list of plural terms. 


---

## <kbd>function</kbd> `get_transform_terms_staring`

```python
get_transform_terms_staring(project: Project) → List[str]
```

Get terms used to start transformations for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve starting transformation terms. 



**Returns:**
 
 - <b>`list`</b>:  A list of starting transformation terms.  


---

## <kbd>function</kbd> `get_transform_terms_inner`

```python
get_transform_terms_inner(project: Project) → List[str]
```

Get terms used within transformations for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve inner transformation terms. 



**Returns:**
 
 - <b>`list`</b>:  A list of inner transformation terms. 



**Note:**

> This function retrieves inner transform terms, which differ from starting transform terms (see `get_transform_terms_starting`). Inner transform terms are words that describe the transformation process within sentences, while starting transform terms often indicate the beginning of a transformation action. 


---

## <kbd>function</kbd> `get_conditional_terms`

```python
get_conditional_terms(project: Project) → List[str]
```

Get conditional terms for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve conditional terms. 



**Returns:**
 
 - <b>`list`</b>:  A list of conditional terms. 


---

## <kbd>function</kbd> `get_validate_terms`

```python
get_validate_terms(project: Project) → List[str]
```

Get validation terms for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve validation terms. 



**Returns:**
 
 - <b>`list`</b>:  A list of validation terms. 


---

## <kbd>function</kbd> `get_boolean_terms`

```python
get_boolean_terms(project: Project) → List[str]
```

Get boolean terms for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve boolean terms. 



**Returns:**
 
 - <b>`list`</b>:  A list of boolean terms. 


---

## <kbd>function</kbd> `get_get_terms`

```python
get_get_terms(project: Project) → List[str]
```

Get terms related to retrieving data for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve data retrieval terms. 



**Returns:**
 
 - <b>`list`</b>:  A list of data retrieval terms. 


---

## <kbd>function</kbd> `get_set_terms`

```python
get_set_terms(project: Project) → List[str]
```

Get terms related to setting data for a project. 



**Args:**
 
 - <b>`project`</b>:  The project for which to retrieve data setting terms. 



**Returns:**
 
 - <b>`list`</b>:  A list of data setting terms. 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
