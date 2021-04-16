###Install docker and docker-compose  
[guide](https://docs.docker.com/compose/install/)  

### Link for Plateform and WebApp
[Plateform](https://code.jtg.tools/rishabh.bansal/todo-platform)  
[WebApp](https://code.jtg.tools/rishabh.bansal/todo-webapp)

**Changes**
```
web:
    build: <Plateform-directory>/backend
    container_name: web2
```
```
frontend:
    build: <Webapp-directory>/frontend
    container_name: frontend2
```
**docker-compose build .**
**docker-compose up -d**
