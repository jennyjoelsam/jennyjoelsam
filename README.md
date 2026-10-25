<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="Terminal: Jenny Joel Sam, Python backend and AI engineer" src="assets/banner-dark.svg" width="900">
</picture>

<br>

[![Email](https://img.shields.io/badge/email-jennyjoelsamp%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=3fb950&labelColor=0d1117&color=30363d)](mailto:jennyjoelsamp@gmail.com)
[![Location](https://img.shields.io/badge/location-Hyderabad%2C%20IN-0d1117?style=flat-square&logo=googlemaps&logoColor=58a6ff&labelColor=0d1117&color=30363d)](#)
[![Status](https://img.shields.io/badge/status-open%20to%20work-0d1117?style=flat-square&logo=statuspage&logoColor=3fb950&labelColor=0d1117&color=3fb950)](mailto:jennyjoelsamp@gmail.com)

</div>

## `$ cat about.md`

B.Tech CSE '25. I'm becoming a solid **Python backend developer**, then moving into **GenAI systems**: retrieval, evaluation, LLM APIs. I learn by building small, tested projects and writing down what I can and can't explain yet.

```yaml
focus:      python backend -> rag / genai
building:   kb-api next steps (BM25, embeddings)
learning:   sql, testing habits, system design basics
looking_for: entry-level python / backend / junior ai roles
```

## `$ ls projects/`

### [kb-api](https://github.com/jennyjoelsam/kb-api) &nbsp;![tests](https://github.com/jennyjoelsam/kb-api/actions/workflows/tests.yml/badge.svg)

A FastAPI + SQLite REST service for storing and searching text documents. The foundation for a RAG support assistant.

```text
client ──► FastAPI (main.py) ──► crud.py ──► SQLAlchemy ──► SQLite
              │                      └──► search.py  (ranked: title 3x, tag 2x, body 1x)
              └──► Pydantic schemas (422 on bad input, 404 on missing)
```

| | |
|---|---|
| **API** | CRUD, tag filter, pagination, ranked keyword search, `/health` |
| **Quality** | 32 pytest tests, GitHub Actions CI on every push |
| **Ops** | Dockerfile, env-based config, request logging |
| **Honest limits** | No stemming, no auth, search scans all docs. Listed in the README |

**Roadmap:** BM25 + embedding search → RAG answers with citations → evaluation set.

## `$ cat stack.txt`

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=3776AB">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=009688">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-0d1117?style=for-the-badge&logo=sqlite&logoColor=58a6ff">
  <img alt="Pytest" src="https://img.shields.io/badge/pytest-0d1117?style=for-the-badge&logo=pytest&logoColor=0A9EDC">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=2496ED">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-0d1117?style=for-the-badge&logo=githubactions&logoColor=2088FF">
  <img alt="Git" src="https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=F05032">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-0d1117?style=for-the-badge&logo=scikitlearn&logoColor=F7931E">
</p>

## `$ cat certifications.txt`

- IABAC Data Science Foundation
- IABAC AI Expert
- Microsoft Azure AI Fundamentals
- Google AI Essentials

## `$ ./contributions --animate`

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jennyjoelsam/jennyjoelsam/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jennyjoelsam/jennyjoelsam/output/snake.svg">
  <img alt="Contribution graph snake animation" src="https://raw.githubusercontent.com/jennyjoelsam/jennyjoelsam/output/snake.svg">
</picture>
</div>

## `$ mail -s "hello" jennyjoelsamp@gmail.com`

Email is the fastest way to reach me.
