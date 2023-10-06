<!-- markdownlint-disable -->

# <kbd>module</kbd> `nlp.pos_tag`





---

## <kbd>function</kbd> `generate_tag`

```python
generate_tag(project: Project, term: str) → str
```

Generate a part-of-speech (POS) tag for a given term in a specific project. 

This function first checks if the term is present in a custom dictionary specific to the project. If the term is found in the custom dictionary, the corresponding POS tag is returned. If the term is not in the custom dictionary, it uses the Stanford Part-of-Speech Tagger to generate the POS tag. 



**Args:**
 
 - <b>`project`</b> (str):  The name of the project or context in which the term is being analyzed. 
 - <b>`term`</b> (str):  The input term for which the POS tag is to be generated. 



**Returns:**
 
 - <b>`str`</b>:  The POS tag for the input term. 


---

## <kbd>function</kbd> `get_tag_text`

```python
get_tag_text(tag: str) → <enum 'POSType'>
```

Returns the part of speech type of a given tag. 



**Args:**
 
 - <b>`tag`</b> (str):  The tag to be analyzed. 



**Returns:**
 
 - <b>`POSType`</b>:  The part of speech type of the tag. 


---

## <kbd>class</kbd> `POSType`
An enumeration. 







---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
