<div align="center">

# Adi

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=20&pause=1500&color=36BCF7&center=true&vCenter=true&width=560&height=40&lines=CS+fundamentals%2C+not+library+calls;Math+first%2C+then+code;Independent+learner+%7C+India" alt="typing animation" />

[![GitHub](https://img.shields.io/badge/GitHub-GiTaDi--CrEaTe-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/GiTaDi-CrEaTe)
[![Email](https://img.shields.io/badge/Email-kar323834%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kar323834@gmail.com)

</div>

<br>

I work on the theoretical foundations of computer science — algorithms, linear algebra, probability, and machine learning — and I build things by deriving them, not by importing them. If a problem can be solved by calling `.fit()`, I'd rather first understand what's happening inside the call.

<br>

## Currently building — [MIT-OCW-Portfolio](https://github.com/GiTaDi-CrEaTe/MIT-OCW-Portfolio)

A self-directed study through six MIT OpenCourseWare subjects — discrete math, linear algebra, algorithms, probability, machine learning, and AI search — where every core algorithm is implemented from first principles: **NumPy only, no scikit-learn, no PyTorch.**

Why build it this way:

- **A library call proves you can use a tool. A from-scratch implementation proves you understand what the tool is doing.** Writing backpropagation by hand means deriving every gradient via the chain rule — not trusting autograd to get it right.
- **Every script verifies itself against ground truth**, not just "the output looks reasonable." The neural net's hand-derived gradients are checked against finite-difference approximation. The from-scratch SVD is checked against `numpy.linalg`. Dijkstra is checked against brute-force relaxation. A* is checked against Dijkstra for optimality while counting the nodes it saves.
- **The proof is in numbers, not adjectives** — e.g. a linear classifier fails at 54.7% accuracy on a task a 2-hidden-layer network solves at 100%, demonstrating *why* non-linearity matters instead of asserting it.

<br>

## Open source — pandas / Apache Arrow

[![pandas PR merged](https://img.shields.io/badge/pandas--dev%2Fpandas-%2365647_merged-2ea44f?style=flat-square&logo=pandas&logoColor=white)](https://github.com/pandas-dev/pandas/pull/65647)
[![Arrow issue fixed](https://img.shields.io/badge/apache%2Farrow-%2350312_fixed-2ea44f?style=flat-square&logo=apachespark&logoColor=white)](https://github.com/apache/arrow/issues/50312)

Added a test verifying that `to_parquet` / `read_parquet` correctly round-trips `uuid.UUID` objects through PyArrow. While iterating on it across review rounds, the test surfaced a real regression: on Python 3.14 / nightly builds, PyArrow was failing to cast `FIXED_LEN_BYTE_ARRAY` data back into `UUID` objects, silently returning raw bytes instead. Traced it to PyArrow's `pandas_compat` casting layer, filed [apache/arrow#50312](https://github.com/apache/arrow/issues/50312) with a minimal repro, and the fix was merged upstream a few weeks later — closing the loop from "this test looks flaky" to "found and reported an actual upstream bug."

<br>

## Engineering Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**AI, Math & Data Science**  
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

**Backend & Databases**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Systems, DevOps & Architecture**  
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-019733?style=flat-square&logo=vim&logoColor=white)
![Tmux](https://img.shields.io/badge/Tmux-1BB91F?style=flat-square&logo=tmux&logoColor=white)

<br>

## Philosophy

> Show, don't tell. If I can't derive it, I can't claim to understand it. If the code can't be checked against ground truth, it isn't proof of anything.

<br>

## Activity & Analytics

<p align="center">
  <em>"Price is what you pay. Value is what you get."</em><br>
  <em>"Code is ink; documentation is the footnote."</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Lines_of_Code-1.06M+-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Lines of Code" />
</p>

<p align="center">
  <a href="https://wakatime.com/@Adi00x1add">
    <img src="https://github-readme-stats.vercel.app/api/wakatime?username=Adi00x1add&layout=compact&theme=radical&hide_border=true" alt="WakaTime Stats" />
  </a>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=GiTaDi-CrEaTe&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=GiTaDi-CrEaTe&theme=radical&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=GiTaDi-CrEaTe&bg_color=0D1117&color=36BCF7&line=36BCF7&point=FFFFFF&area=true&hide_border=true" alt="Activity Graph" />
</p>

---

### GitHub Trophies

<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=GiTaDi-CrEaTe&theme=radical&no-frame=true&no-bg=true&margin-w=15" alt="Trophies" />
  </a>
</p>

---

### Contribution City & Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/GiTaDi-CrEaTe/GiTaDi-CrEaTe/main/profile-3d-contrib/profile-night-view.svg" alt="3D Graph" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GiTaDi-CrEaTe/GiTaDi-CrEaTe/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/GiTaDi-CrEaTe/GiTaDi-CrEaTe/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Grid Snake" src="https://raw.githubusercontent.com/GiTaDi-CrEaTe/GiTaDi-CrEaTe/output/github-contribution-grid-snake.svg">
  </picture>
</p>
