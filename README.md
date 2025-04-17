## 👋 Welcome to My GitHub!
### 💻 AI Engineer | 🌍 Speech Processing & NLP | 🚀 Python & ML, Django & FastAPI Developer


---

<p style="text-align: center;">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&color=%2336BCF7&size=25&duration=3000&pause=500&center=true&vCenter=true&width=1000&lines=Hi+👋,+Friends!;My+name+is+Shymaa+Medhat.;I'm+an+AI+Engineer+and+Machine+Learning+Developer." alt="Typing SVG" />
</p>


<p align="center">
  <a href="https://github.com/Shymaa2611"><img src="https://img.shields.io/badge/GitHub-0e75b6?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/shymaa-medhat-4104b0289"><img src="https://img.shields.io/badge/LinkedIn-0e75b6?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://www.facebook.com/shaymaa.madhetahmed"><img src="https://img.shields.io/badge/Facebook-0e75b6?style=for-the-badge&logo=facebook&logoColor=white"></a>
  <a href="https://www.instagram.com/shaymaamadhetahmed"><img src="https://img.shields.io/badge/Instagram-0e75b6?style=for-the-badge&logo=instagram&logoColor=white"></a>
  <a href="https://drive.google.com/file/d/1YN8eXd4_ow11XRQYCqvIgMaYbP8uvZnE/view?usp=drive_link"><img src="https://img.shields.io/badge/Resume-CV-0e75b6?style=for-the-badge&logo=googledrive&logoColor=white"></a>
</p>


```python
from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()

class Introduction(BaseModel):
    name: str = 'Shymaa Medhat'
    job_title: str = 'AI Engineer'
    knowledge: list = ['Python','Django','FastAPI','Pytorch', 'TensorFlow', 'Transformers', 'PostgreSQL', 'MongoDB']

@app.post("/introduce_yourself")
async def introduce_yourself(request: Introduction):
    name = request.name
    job_title = request.job_title
    knowledge = ', '.join(request.knowledge)

    introduction = f"Hello, my name is {name}. I am a {job_title} and I have Knowledge in {knowledge}."

    return {'introduction': introduction}
```

### About Me
Passionate AI Engineer with a deep interest in Speech Processing, NLP, and developing real-world applications. From REST APIs to model training, I strive to blend cutting-edge technology with practical, scalable solutions.

---

<h3 align="left">Languages and Tools:</h3>
<table>
  <tr>
    <td><b>Programming Languages</b></td>
    <td>Python, C++ , C , Dart , JavaScript </td>
  </tr>
  <tr>
    <td><b>Frameworks</b></td>
    <td>Django, FastAPI, PyTorch, TensorFlow</td>
  </tr>
  <tr>
    <td><b>Databases</b></td>
    <td>PostgreSQL, MongoDB</td>
  </tr>
  <tr>
    <td><b>Tools & Technologies</b></td>
    <td>Docker, Git, GraphQL, Postman</td>
  </tr>
</table>

---

### Technologies I Love

- 🐍 **Python**: Django, FastAPI, PyTorch, TensorFlow, Transformers, Speech Processing, NLP
- 🗄️ **Databases**: PostgreSQL, MongoDB
- 🌐 **API Development**: RESTful APIs, GraphQL
- 📦 **Deployment**: Docker, PythonAnywhere

---

### Facts

- 💡 "Programming is the art of turning imagination into reality."
- 🌱 Always learning and evolving in the world of AI and NLP.
- 🚀 On a mission to make machines understand human language!



