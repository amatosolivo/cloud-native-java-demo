# Reservation Service

**A sample application without UI that allows to add and view reservation(s) for an individual**

This is a proof-of-concept application, which demonstrates [Microservice Architecture Pattern](http://martinfowler.com/microservices/) using Spring Boot and Spring Cloud.

<!--<p align="centre">
  <img style="float: centre;" width="200" align="centre" alt="Functional Services" src="https://cloud.githubusercontent.com/assets/3782824/22767852/22d5ecae-eea4-11e6-8026-818383af8e1e.png">
</p>
.
.center[![Functional Services](https://cloud.githubusercontent.com/assets/3782824/22767852/22d5ecae-eea4-11e6-8026-818383af8e1e.png)]-->

<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/3782824/22767852/22d5ecae-eea4-11e6-8026-818383af8e1e.png">
</p>

#### Reservation service
Contains general user input logic for creating reservations and viewing them.

Method	| Path	| Description	| User authenticated	| Available from UI
------------- | ------------------------- | ------------- |:-------------:|:----------------:|
GET	| /reservations/names	| Gets list of users who have reserved	| × | 	×
POST	| /reservations/	| Does reservation for a given user 	|   | ×

