<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFD6E0,100:FFABAB&height=160&section=header&text=Useless%20Facts&fontSize=52&fontColor=333333&fontAlignY=38&desc=3%2C000%2B%20verified%20facts%20%E2%80%94%20free%20forever&descAlignY=60&descSize=16" />

<br/>



![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1200&color=888888&center=true&vCenter=true&width=500&lines=Sharks+existed+before+trees.;Oxford+University+is+older+than+the+Aztec+Empire.;A+day+on+Venus+is+longer+than+its+year.;Wombat+poop+is+cube-shaped.;Otters+hold+hands+while+sleeping.)



<br/>



![Facts](https://img.shields.io/badge/Facts-3%2C000%2B-FF6B6B?style=flat-square)




![License](https://img.shields.io/badge/License-MIT-4ECDC4?style=flat-square)




![Maintained](https://img.shields.io/badge/Maintained%20by-Endroid%20Inc.-45B7D1?style=flat-square)




![PRs](https://img.shields.io/badge/PRs-Welcome-96CEB4?style=flat-square)



</div>

---

## About

**Useless Facts** is an open dataset of over 3,000 verified, standalone facts spanning science, history, nature, space, language, psychology, medicine, philosophy, and more — published freely under the MIT License by **Endroid Inc.**

Every fact is accurate, self-contained, and ready to use in any project.

---

## Coverage

| Domain | Domain | Domain |
|---|---|---|
| Science & Physics | Human Biology | Space & Astronomy |
| World History | Animals & Nature | Geography |
| Language & Linguistics | Psychology | Medicine |
| Technology | Architecture | Philosophy |
| Mathematics | Environment | Culture & Society |

---

## Quick Start

```bash
# Clone
git clone https://github.com/wized2/Useless-Facts.git
cd Useless-Facts

# Random fact
shuf -n 1 facts.txt

# Search by topic
grep -i "ocean" facts.txt
```

---

## Usage

**Python**
```python
import random

with open("facts.txt", "r", encoding="utf-8") as f:
    facts = [line.strip() for line in f if line.strip()]

print(random.choice(facts))
```

**JavaScript**
```javascript
const fs = require("fs");
const facts = fs.readFileSync("facts.txt", "utf-8").split("\n").filter(Boolean);
console.log(facts[Math.floor(Math.random() * facts.length)]);
```

---

## Built For



![Trivia Apps](https://img.shields.io/static/v1?label=&message=Trivia%20Apps&color=FF6B6B&style=flat-square)




![Discord Bots](https://img.shields.io/static/v1?label=&message=Discord%20Bots&color=4ECDC4&style=flat-square)




![Flash Cards](https://img.shields.io/static/v1?label=&message=Flash%20Cards&color=45B7D1&style=flat-square)




![NLP Datasets](https://img.shields.io/static/v1?label=&message=NLP%20Datasets&color=96CEB4&style=flat-square)




![Quiz Games](https://img.shields.io/static/v1?label=&message=Quiz%20Games&color=FFEAA7&style=flat-square)




![Mobile Apps](https://img.shields.io/static/v1?label=&message=Mobile%20Apps&color=DDA0DD&style=flat-square)




![Newsletters](https://img.shields.io/static/v1?label=&message=Newsletters&color=98D8C8&style=flat-square)




![Browser Extensions](https://img.shields.io/static/v1?label=&message=Browser%20Extensions&color=F7DC6F&style=flat-square)




![Educational Tools](https://img.shields.io/static/v1?label=&message=Educational%20Tools&color=BB8FCE&style=flat-square)



---

## Contributing

Open a pull request with your additions. All facts must be accurate, verifiable, and fully self-contained.

```bash
git checkout -b your-branch
# Edit facts.txt
git commit -m "add: [description]"
git push origin your-branch
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFABAB,100:FFD6E0&height=100&section=footer" />



![Endroid](https://img.shields.io/badge/Endroid%20Inc.-endroid.pages.dev-FF6B6B?style=flat-square)




![GitHub](https://img.shields.io/badge/GitHub-wized2-4ECDC4?style=flat-square&logo=github&logoColor=white)



**Free to use. Free to share. Free forever.**

*Copyright 2025 Endroid Inc. — MIT License*

</div>
