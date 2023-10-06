<!-- markdownlint-disable -->

# <kbd>module</kbd> `common.error_handler`





---

## <kbd>function</kbd> `handle_error`

```python
handle_error(
    module: str,
    message: str,
    severity: ErrorSeverity = <ErrorSeverity.Warning: 1>,
    exit_system: bool = False,
    exception=None
) → None
```

Handle and log error messages with specified severity. 



**Args:**
 
 - <b>`module`</b> (str):  The name of the module where the error occurred. 
 - <b>`message`</b> (str):  The error message to be logged. 
 - <b>`severity`</b> (ErrorSeverity):  The severity level of the error (default is ErrorSeverity.Warning). 
 - <b>`exit_system`</b> (bool):  Whether to exit the system after logging the error (default is False). 
 - <b>`exception`</b> (Exception or None):  Optional exception associated with the error (default is None). 


---

## <kbd>class</kbd> `ErrorSeverity`
Enumeration representing error severity levels. Values:  Warning (int): Represents a warning severity.  Error (int): Represents an error severity.  Critical (int): Represents a critical severity. 







---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
