<!-- markdownlint-disable -->

# <kbd>module</kbd> `nlp.splitter`






---

## <kbd>class</kbd> `Splitter`
Singleton class for splitting text. 

This class provides methods for splitting text into word tokens, splitting names using ronin, and using a heuristic approach for splitting names based on a custom dictionary. 



**Attributes:**
 
 - <b>`project`</b> (Project):  The Project instance with all necessary configurations in it. 




---

### <kbd>method</kbd> `set_project`

```python
set_project(project: Project)
```





---

### <kbd>method</kbd> `split_heuristic`

```python
split_heuristic(name: str) → List[str]
```

Split a name using a heuristic approach based on a custom dictionary. 

Unlike other methods in this class, 'split_heuristic' uses a heuristic approach that relies on a custom dictionary to split names. It replaces terms in the name with placeholders, performs the split, and then restores the original terms. 



**Args:**
 
 - <b>`name`</b> (str):  The name to split. 



**Returns:**
 
 - <b>`list`</b>:  A list containing the split parts of the name. 

---

### <kbd>method</kbd> `split_word_tokens`

```python
split_word_tokens(text: str) → List[str]
```

Split text into word tokens. 



**Args:**
 
 - <b>`text`</b> (str):  The input text to split. 



**Returns:**
 
 - <b>`list`</b>:  A list of word tokens. 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
