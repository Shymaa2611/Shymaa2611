<p>
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&red=%23FF0000&size=25&duration=3000&pause=503&center=true&vCenter=true&width=1000&lines=Hi 👋+Friends;My+name+is+Shymaa+Medhat+.;I+am+AI+Engineer;"  alt="Typing SVG"  />
</a>
</p>
<br/>

<span align="left"><a href="https://github.com/Shymaa2611"> <img src="https://komarev.com/ghpvc/?username=shymaa2611&label=Github&color=0e75b6&style=flat" alt="shymaa2611" /> </a></span>
<span align="left"><a href="https://www.linkedin.com/in/shymaa-medhat-4104b0289"> <img src="https://komarev.com/ghpvc/?username=shymaa2611&label=LinkedIn&color=0e75b6&style=flat" alt="shymaa2611" /> </a></span>
<span align="left"><a href="https://www.facebook.com/shaymaa.madhetahmed?mibextid=b06tZ0"> <img src="https://komarev.com/ghpvc/?username=shymaa2611&label=Facebook&color=0e75b6&style=flat" alt="shymaa2611" /> </a></span>
<span align="left"><a href="https://drive.google.com/file/d/1G-dXGrYehko6EqFwIoaNnunq8QSStCj0/view?usp=drive_link"><img src="https://komarev.com/ghpvc/?username=shymaa2611&label=CV&color=0e75b6&style=flat" alt="shymaa2611" /></a></span>
<p>

  ```python
from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()

class Introduction(BaseModel):
    name: str = 'Shymaa Medhat'
    job_title: str = 'AI Engineer'
    knowledge: list = ['Python','Django','FastAPI','Pytorch', 'TensorFlow', 'Transformers','Speech Processing', 'PostgreSQL', 'MongoDB']

@app.post("/introduce_yourself")
async def introduce_yourself(request: Introduction):
    name = request.name
    job_title = request.job_title
    knowledge = ', '.join(request.knowledge)

    introduction = f"Hello, my name is {name}. I am a {job_title} and I have Knowledge in {knowledge}."

    return {'introduction': introduction}
```
</p>



<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://graphql.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/graphql/graphql-icon.svg" alt="graphql" width="40" height="40"/> </a>  <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
<a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://seeklogo.com/images/F/fastapi-logo-541BAA112F-seeklogo.com.png" alt="selenium" width="40" height="40"/> </a>
  <a href="https://huggingface.co/" target="_blank" rel="noreferrer"> 
    <img src="https://avatars.githubusercontent.com/u/25720743?s=200&v=4" alt="huggingface" width="40" height="40"/> 
  </a>
<a href="https://pytorch.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original-wordmark.svg" alt="pytorch" width="40" height="40"/> 
  </a>
  <a href="https://www.tensorflow.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original-wordmark.svg" alt="tensorflow" width="40" height="40"/> 
  </a>

</p>
## Technologies I Love

- 💻 Python (Django,FastAPI,Pytorch,Tensorflow,transformers,Speech Processing,NLP)
- 🗄️ Relational and NoSQL Databases (PostgreSQL, MongoDB)
- 🚀 RESTful API Development and Graphql
- 🌐 Server Deployment and Management (Docker,pythonanywhere)

- ⚡ fact: ...
- Programming is the art of turning imagination into reality

