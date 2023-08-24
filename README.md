<h1 align="center">Hi 👋, I'm Backend Developer</h1>
<h3 align="center">I'm interested in [ Django Framework - FastAPI ]</h3>
<span align="left"><a href="https://github.com/Shymaa2611"> <img src="https://komarev.com/ghpvc/?username=shymaa2611&label=Github&color=0e75b6&style=flat" alt="shymaa2611" /> </a></span>
<span align="left"><a href="https://www.linkedin.com/in/shymaa-medhat-4104b0289"> <img src="https://komarev.com/ghpvc/?username=shymaa2611&label=LinkedIn&color=0e75b6&style=flat" alt="shymaa2611" /> </a></span>
<span align="left"><a href="https://www.facebook.com/shaymaa.madhetahmed?mibextid=b06tZ0"> <img src="https://komarev.com/ghpvc/?username=shymaa2611&label=Facebook&color=0e75b6&style=flat" alt="shymaa2611" /> </a></span>

'''
from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()

class IntroductionRequest(BaseModel):
    name: str = 'Shymaa Medhat'
    occupation: str = 'Backend Developer'
    interests: list = ['Python', 'FastAPI', 'Rest Framework', 'Graphql', 'Swagger', 'PostgreSQL', 'MongoDB']

@app.post("/introduce_yourself")
async def introduce_yourself(request: IntroductionRequest):
    name = request.name
    job_title = request.occupation
    interests = ', '.join(request.interests)

    introduction = f"Hello, my name is {name}. I am a {job_title} and I'm interested in {interests}."

    return {'introduction': introduction}


'''

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://graphql.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/graphql/graphql-icon.svg" alt="graphql" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
<a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://seeklogo.com/images/F/fastapi-logo-541BAA112F-seeklogo.com.png" alt="selenium" width="40" height="40"/> </a>
</p>

- ⚡ Fun fact: ...
-->
