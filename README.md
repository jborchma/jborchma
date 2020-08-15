```python
from typing import List

class Borchmann:

    def __init__(self):
        self.username: str = "jborchma"
        self.name: str = "Jan Borchmann"
        self.location: str = "Toronto, ON"
        self.languages: List[str] = ["English", "German", "Spanish", "Python"]
        self.hobbies: List[str] = ["📊", "🚲", "⚽️", "🏒", "✈️", "🎸", "🍺"]
        self.workplace: str = "Capital One"
        self.job: str = "Data Scientist"

    def __str__(self):
        return self.name


if __name__ == "__main__":
    me = Borchmann()
```
