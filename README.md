```python
import os
import json

info = {
  "name": "MistaFeast",
  "age": 16,
  "languages": {
    "learned": [
      "python",
      "javascript",
      "lua"
    ],
    "learning": [
      "C++",
      "ASM",
      "HTML/CSS" # Not really programming languages but whatever
    ]
  }
}

with open(os.path.join(os.path.expanduser(r"~\Documents"), "information.json"), "w") as f:
  f.write(json.dumps(info))
```

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MistaFeast&theme=dark&show_icons=true" alt="statistics" />  
  <br>
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MistaFeast&theme=dark&layout=compact" alt="languages" />
</p>
