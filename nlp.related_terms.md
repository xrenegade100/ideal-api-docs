<!-- markdownlint-disable -->

# <kbd>module</kbd> `nlp.related_terms`





---

## <kbd>function</kbd> `remove_stopwords`

```python
remove_stopwords(term_list: List[str]) → List[str]
```

Remove stopwords from a list of terms. 



**Args:**
 
 - <b>`term_list`</b> (List[str]):  The list of terms from which stopwords are to be removed. 



**Returns:**
 
 - <b>`List[str]`</b>:  A list of terms with stopwords removed. 


---

## <kbd>function</kbd> `clean_text`

```python
clean_text(text: Union[str, List[str]], return_unique: bool = False) → List[str]
```

Clean and tokenize text. 



**Args:**
 
 - <b>`text`</b> (Union[str, List[str]]):  The input text as a string or a list of strings. 
 - <b>`return_unique`</b> (bool, optional):  Whether to return unique tokens. Default is False. 



**Returns:**
 
 - <b>`List[str]`</b>:  A list of cleaned and tokenized words from the input text. 


---

## <kbd>function</kbd> `are_antonyms`

```python
are_antonyms(term1: str, term2: str) → bool
```

Check if two terms are antonyms. 



**Args:**
 
 - <b>`term1`</b> (str):  The first term. 
 - <b>`term2`</b> (str):  The second term. 



**Returns:**
 
 - <b>`bool`</b>:  True if the terms are antonyms, False otherwise. 


---

## <kbd>function</kbd> `get_synonyms`

```python
get_synonyms(term: str, pos: str) → set[str]
```

Get synonyms for a term based on its part-of-speech (POS). 



**Args:**
 
 - <b>`term`</b> (str):  The term for which synonyms are to be retrieved. 
 - <b>`pos`</b> (str):  The part-of-speech (POS) of the term. 



**Returns:**
 
 - <b>`set`</b>:  A set of synonyms for the given term and POS. 


