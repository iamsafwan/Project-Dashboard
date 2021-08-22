# Welcome to Project Dashboard  :tada: 
**REST API Dashboard Repository**

The project was created as coursework when I was studying at the Queen Mary University of London.

![Progress Image](/static/Welcome.png)

![Progress Image](/static/About.png)

![Progress Image](/static/Dashboard.png)

![Progress Image](/static/Records.png)

**Full source code of the project will be uploaded soon.**

## The Dashboad is powered by
**Backend:**
- Python
- Flask
- SQL Alchemy
- Cassandra
- Firebase

**Frontend:**
- HTML
- CSS

**Containerized:**
- Docker
- Kubernetes

**Architecture:**
- Microservices

**Security:**
- HTTPS
- Hashes
- User Access Management

### Getting Started

```
Installing via requirements.txt:
$ git clone https://github.com/iamsafwan/taskmgr.git
$ python pip install -r requirements.txt
$ python app.py
```


### Public routes

GET [`/api/v5/advice`] (get all advice)

### Protected routes

POST `/api/v5/covid_19total` 
- required params: `country`, `apikey`

POST `/api/v5/covid_19/<location>` 
- required params: `country`, `apikey`

POST `/api/v5/fx/<country>` 
- required params: `country`, `apikey`

DELETE: `/api/v5/fxr/<fcountry>/<tcountry>` 
- required params: `country`, `apikey`

### Authentication

GET `/dashboard` (user login)
- opens login page

After successful login, user will be redirected to client app. 

GET `/showrecords` (get userdata)
- returns info on users



### Dependencies
- Install flask
- Install flask_sqlalchemey
- Install request_cache
- Install pyopenssl
