# Django-React Blog
Using [Django backend, React front, ](https://medium.com/swlh/how-to-deploy-django-rest-framework-and-react-redux-application-with-docker-fa902a611abf)

Using dockerfile.react to create react files. DOESNT WORK, GAVE UP ON REACT PART. YARN START says CANT FIND A FILE.
```
docker run -it --rm -v ${PWD}/blog_frontend:/app {{img name}} npx create-react-app .

docker run -it --rm -v ${PWD}/blog_frontend:/app {{img name}}yarn add antd redux axios react-redux redux-thunk redux-logger
```