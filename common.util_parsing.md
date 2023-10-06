<!-- markdownlint-disable -->

# <kbd>module</kbd> `common.util_parsing`




**Global Variables**
---------------
- **SRCML_URL**

---

## <kbd>function</kbd> `get_class_attribute_names`

```python
get_class_attribute_names(entity_class: Class) → List[str]
```

Get the names of attributes for a given entity class. 



**Args:**
 
 - <b>`entity_class`</b> (Entity):  The entity class for which attribute names are retrieved. 



**Returns:**
 
 - <b>`List[str]`</b>:  A list of attribute names. 


---

## <kbd>function</kbd> `get_all_items_in_class`

```python
get_all_items_in_class(entity_class: Class) → List[str]
```

Get all items (class, attributes, methods, variables, and parameters) in a given entity class. 



**Args:**
 
 - <b>`entity_class`</b> (Entity):  The entity class for which items are retrieved. 



**Returns:**
 
 - <b>`List[str]`</b>:  A list of all items in the entity class, including the class itself, attributes, methods, variables, and parameters. 


---

## <kbd>function</kbd> `get_all_class_fields`

```python
get_all_class_fields(entity_class: Class)
```

Get all class fields (attributes, method variables, and method parameters) in a given entity class. 



**Args:**
 
 - <b>`entity_class`</b> (Entity):  The entity class for which class fields are retrieved. 



**Returns:**
 
 - <b>`List[str]`</b>:  A list of all class fields in the entity class, including attributes, method variables, and method parameters. 


---

## <kbd>function</kbd> `get_all_exception_throws`

```python
get_all_exception_throws(method)
```






---

## <kbd>function</kbd> `get_all_return_statements`

```python
get_all_return_statements(method)
```






---

## <kbd>function</kbd> `get_all_function_calls`

```python
get_all_function_calls(method)
```






---

## <kbd>function</kbd> `get_all_conditional_statements`

```python
get_all_conditional_statements(method)
```






---

## <kbd>function</kbd> `is_test_method`

```python
is_test_method(
    project,
    entity: Entity,
    identifier: Union[Class, Attribute, Property, Method, Variable, Parameter]
) → bool
```

Check if an identifier is a test method within a given project and entity. 



**Args:**
 
 - <b>`project`</b>:  The project to which the entity belongs. 
 - <b>`entity`</b> (Entity):  The entity to which the identifier belongs. 
 - <b>`identifier`</b> (Union[Class, Attribute, Property, Method, Variable, Parameter]):  The identifier being checked. 



**Returns:**
 
 - <b>`bool`</b>:  True if the identifier is a test method; False otherwise. 


---

## <kbd>function</kbd> `is_boolean_type`

```python
is_boolean_type(
    entity: Entity,
    identifier: Union[Class, Attribute, Property, Method, Variable, Parameter]
) → bool
```

Check if an identifier has a boolean data type in the context of a given entity. 



**Args:**
 
 - <b>`entity`</b> (Entity):  The entity in which the identifier is defined. 
 - <b>`identifier`</b> (Union[Class, Attribute, Property, Method, Variable, Parameter]):  The identifier being checked. 



**Returns:**
 
 - <b>`bool`</b>:  True if the identifier has a boolean data type; False otherwise. 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
