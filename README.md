# Gym Log

Full Stack Django & React Web App with JWT authentication.

This repo can be used as a starting point for developing a production-ready application using Django, React, and
Postgres in a Dockerized environment with deployment to Heroku.


## Local deployment

1) Install docker: https://docs.docker.com/get-docker/
2) Clone github repo.
3) Run: `docker-compose up --build`.

To access the fronted part of application open [http://localhost:3000](http://localhost:3000) in your browser.

To view `Swagger API endpoints` open [http://localhost:8000/swagger/](http://localhost:8000/swagger/) in your browser.

To view `Django admin site` open [http://localhost:8000/admin/](http://localhost:8000/admin/) in your browser.


### Main tools and libraries

Backend:

- `Django` as a web framework.
- `Django REST framework` for building web APIs, serialization, and deserialization.
- `JWT authentication` for securely transmitting information between frontend and backend applications.
- `PostgreSQL` as a database in production.

Frontend:

- `React` for building user interface.
- `React Bootstrap` for simplifying the creation and styling of React components.
- `React Query` for managing server state, getting data from the backend, and updating it.
- `Redux` for managing application state. And `Redux Persist` to store state between page reloads.
- `Formik` and `Yup` for object schema validation for login and register pages.

### Ideas for improvement

- Add logic for email confirmation on registration.
- Add logic for password reset on the login page.
- Add internationalization for several languages.
