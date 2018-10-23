
https://www.flowable.org/downloads.html


docker run -p8080:8080 flowable/flowable-rest

Docker
All Flowable UI apps are available on Docker Hub .

To start the Flowable REST app (with a in memory h2 database):

docker run -p8080:8080 flowable/flowable-rest
The API documentation will be available on http://localhost:8080/flowable-rest/docs/ . (login/password: rest-admin/test)

For a quick start with the full Flowable experience run the ‘All-in-One’ Docker image. This image contains Flowable IDM, Modeler, Task and Admin UI apps on a Tomcat container with a in memory H2 database.

docker run -p8080:8080 flowable/all-in-one
Flowable Modeler; http://localhost:8080/flowable-modeler
Flowable Task; http://localhost:8080/flowable-task
Flowable Admin; http://localhost:8080/flowable-admin
Flowable IDM; http://localhost:8080/flowable-idm

(login/password: admin/test)

Take a look at our GitHub repo for other and more advanced configurations.
