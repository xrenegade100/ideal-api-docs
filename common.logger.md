<!-- markdownlint-disable -->

# <kbd>module</kbd> `common.logger`





---

## <kbd>function</kbd> `setup_logger`

```python
setup_logger(
    name: str,
    log_file: str,
    level: int = 20,
    formatting: str = '%(asctime)s %(levelname)s %(message)s'
) → Logger
```

Set up a logger with the specified configuration. 

**Args:**
 
 - <b>`name`</b> (str):  The name of the logger. 
 - <b>`log_file`</b> (str):  The path to the log file. 
 - <b>`level`</b> (int):  The logging level (default is logging.INFO). 
 - <b>`formatting`</b> (str):  The log message formatting using a format string (default is '%(asctime)s %(levelname)s %(message)s').  The format string can include placeholders such as '%(asctime)s' for timestamp, '%(levelname)s' for log level, and '%(message)s' for the log message. 

**Returns:**
 
 - <b>`logging.Logger`</b>:  The configured logger. 




---

_This file was automatically generated via [lazydocs](https://github.com/ml-tooling/lazydocs)._
