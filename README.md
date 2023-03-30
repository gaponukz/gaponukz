# 💫 About Me:
```python
import typing
import dataclasses

LANGUAGE = typing.Literal['fortan', 'c/cpp', 'java', ...]

class UserTechnology(typing.TypedDict):
    name: str
    experience: float
    strong_in_it: bool

@dataclasses.dataclass
class GitHubUser:
    username: str
    name: str
    bio: str
    can_write_in: list[LANGUAGE]
    favorite_language: LANGUAGE
    tech_stack: list[UserTechnology]

if __name__ == '__main__':
    me = GitHubUser(
        username="gaponukz",
        name="Haponyuk Yevhen",
        bio="Freelancer, sudent of mehmat",
        can_write_in=['python', 'js', 'c/cpp', 'solidity'],
        favorite_language="python",
        tech_stack=[
            {"name": "fastapi", "experience": 1.5, "strong_in_it": True},
            {"name": "flask", "experience": 2.5, "strong_in_it": True},
            {"name": "react.js", "experience": 1.5, "strong_in_it": False},
            {"name": "raw frontend", "experience": 4, "strong_in_it": False},
            {"name": "web3", "experience": 1, "strong_in_it": False},
            {"name": "databases/orm", "experience": 3, "strong_in_it": True},
        ]
    )

```
# 📊 GitHub Stats:
![](https://github-readme-streak-stats.herokuapp.com/?user=gaponukz&theme=dark&hide_border=false)<br/>
<br/>
[![](https://visitcount.itsvg.in/api?id=gaponukz&icon=0&color=0)](https://visitcount.itsvg.in)
