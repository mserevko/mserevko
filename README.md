### Hi there 👋

```python
from dataclasses import dataclass
from typing import Sequence



@dataclass(frozen=True)
class Portfolio:
    profile: str = 'Test Automation Engineer'
    hobbies: Sequence[str] = 'Reading fiction', 'Open Source', 'Running'


@dataclass(frozen=True)
class Skills:
    languages: Sequence[str] = 'Python', 'Shell'
    operation_systems: Sequence[str] = 'Linux', 'Unix'
    test_frameworks: Sequence[str] = 'pyats', 'unittest', 'pytest', 'robot framework', 'selenium'
    web_frameworks: Sequence[str] = 'flask'
    code_quality: Sequence[str] = 'pylint'
    CI: Sequence[str] = 'jenkins'
    VCS: Sequence[str] = 'git', 'perforce'
````
