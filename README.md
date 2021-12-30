# <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"> Hi, I'm Vanilla | [![Profile Views](https://gpvc.arturio.dev/plasticsummer)](https://github.com/plasticsummer)

<p align="center">
  <a href="https://t.me/plasticsummer"><img src="https://www.icegif.com/wp-content/uploads/icegif-2013.gif"></a>
    
</p>

<h3>
    
```python
​
import json
from dataclasses import asdict, dataclass


@dataclass
class Stack:
    languages   : tuple[str, ...] = ("Python", "Bash", "HTML", "CSS")
    misc        : tuple[str, ...] = ("Docker", "Linux", "FastAPI")
    ongoing     : tuple[str, ...] = ("Django", "Java", "JavaScript")

    def serialize(self):
        return json.dumps(asdict(self), indent=4)


stack = Stack()
print(stack.serialize())
printf("Добро пожаловать в ванильный мир!"
​

```
</h3>
