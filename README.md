
# Type hints for writing S7SvrSim Scripts 


```python
from s7svrsim import hints

# annotate
S7: hints.S7DB = S7
Logger: hints.Logger = Logger

# now you get IntelliSence
Logger.LogInfo("111111")
```


