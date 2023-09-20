<!-- markdownlint-disable -->

# <kbd>module</kbd> `nlp.pos_tagger_stanford`






---

## <kbd>class</kbd> `POSTaggerStanford`
Singleton class for interacting with the Stanford Part-of-Speech Tagger. 

This class provides methods for initializing the tagger, getting part-of-speech tags for terms, and terminating the tagger process. 



**Attributes:**
 
 - <b>`tagger`</b>:  A PopenSpawn or spawn instance for running the Stanford Part-of-Speech Tagger. 

### <kbd>method</kbd> `__init__`

```python
__init__() → None
```

Initializes the Stanford Part-of-Speech Tagger. 

It sets up the tagger with the required Java environment variables and starts the tagger process. 




---

### <kbd>method</kbd> `get_pos`

```python
get_pos(term: str) → str
```

Get the part-of-speech (POS) tag for a given term. 



**Args:**
 
 - <b>`term`</b> (str):  The input term for which the POS tag is to be obtained. 



**Returns:**
 
 - <b>`str`</b>:  The POS tag for the input term. 



**Note:**

> This method sends the input term to the Stanford Part-of-Speech Tagger and extracts the POS tag from the response. 
>

**Raises:**
 
 - <b>`IndexError`</b>:  If the POS tag cannot be extracted from the tagger's response. 

---

### <kbd>method</kbd> `terminate`

```python
terminate() → None
```

Terminate the Stanford Part-of-Speech Tagger process. 


