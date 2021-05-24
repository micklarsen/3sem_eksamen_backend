# 3 Semester Examination

[![Build Status](https://travis-ci.com/micklarsen/security_backend.svg?branch=main)](https://travis-ci.com/micklarsen/security_backend)

<br>

# Group E8 members:

- [Alexander Pihl](https://github.com/AlexanderPihl)
- [Jean-Poul Leth-Møller](https://github.com/Jean-Poul)
- Mick Larsen (Me)
- [Morten Rasmussen]()
- [Per Kringelbach](https://github.com/cph-pk)

<br>

# Introduction

[Link to Project description](https://drive.google.com/file/d/1KJbXQlUVfwblKARqqhvivvKv12Bh_ECm/view)

This is part of a 3'rd semester examination, at a computer science course at CPH Business, Lyngby.

<br>

# Description

The goal for this project is to build an API which gives the klient information about space shuttle launches, including weather predictions in the given arrea, for "calculating" the possibility of a shuttle launch. If there is time a NASA API for showing pictures of outer  will be implemented.

<br>

### **API endpoints used**

https://thespacedevs.com/llapi 
- Primary GET: https://ll.thespacedevs.com/2.0.0/launch/upcoming?format=json 
- Docs: https://ll.thespacedevs.com/2.1.0/swagger 

https://openweathermap.org/ 
- Docs: https://openweathermap.org/api/one-call-api 

<br>

### **Frontend configuration**

[Delpoyed with surge](http://rocketlaunch.surge.sh/)

The frontend is a single page application (SPA) written in REACT.

<br>

### **Backend configuration**

[Delpoyed on droplet](https://micklarsen.com/3_sem_eksamensprojekt/)

**The Database**

- MySQL Database using Java Persistence API (JPA) (With some JPQL) to achieve ORM.

**RESTFUL Web service**

- JAX-RS to handle REST operations

**Testing**  
Consisting of unit and integration tests using:

- jUnit
- Grizzly webserver
- Hamcrest

**Security**

- BCrypt plus hash/salt configurations.

**CI/CD pipeline**

- Travis configuration with github hooks - Everytime you push, travis builds and deploys

<br>
