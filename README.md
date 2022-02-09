# KBE Project

## Project for "Komponentenbasierte Entwicklung"

_Hochschule für Technik und Wirtschaft Berlin, WiSe21/22_

---

## Table of contents

* [Description](#description)
* [Installation & Run](#installation-and-run)
* [Architecture & Implementation](#architecture-and-implementation)
* [Used Technologies](#used-technologies)
* [Contributors](#contributors)
* [License](#license)

## Description

Welcome to my component-based-development project in the Wintersemester 21/22. My goal was to implement a project consisting of various
services representing an online tool to vote for gifs.<br>

The full project includes:

* Application Microservice
* Calculator Service
* Storage Service
* Gateway Service
* Frontend Service

Which can all be found as submodules to this repo.

## Installation and Run

To run the application you have to clone all projects and start it with the following command.

```sh
./gradlew bootRun
```

If you want to run the application service in the debug mode you can use the following:

```sh
./gradlew bootRun --args='--feature.debug=true' 
```

If you start the application in debug mode the application will not do an external api call, instead it will mock it.<br>

The frontend requires [Node.js](https://nodejs.org/) to run. <br>

```sh
cd <projektfolder>
npm install
```

To start the server

```sh
npm start
```

And open the app in your favourite browser (we recommend [Firefox](https://www.mozilla.org/en-US/firefox/download/thanks/))
via ```localhost:3000 ```.

## Architecture and Implementation

### Architecture Diagram
<img src="https://i.imgur.com/vEjDTTq.png" alt="Component diagram of the Christmasshop" height="300px">

### Sequence Diagram
<img src="https://i.imgur.com/G1EnCmh.png" alt="Component diagram of the Christmasshop" height="300px">

## Used Technologies

* [JUnit](https://junit.org/junit5/)
* [Gradle](https://gradle.org/)
* [Node.js](https://nodejs.org/)
* [PostgreSQL](https://projectlombok.org/)
* [React](https://reactjs.org/)
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Swagger](https://swagger.io/)
* [Rebex](https://www.rebex.net/tiny-sftp-server/)

## Contributors

|  Name  | MatrikelNr.
| ------ | ------ | 
| Ronyn Brzeski | 0569420

## License

Copyright 2022 Brzeski

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may
obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and
limitations under the License.


<img src="https://c.tenor.com/SYpRfoThETsAAAAC/black-cat-christmas-tree.gif" alt="A lot of black cats are photoshopped together to resemble the shape of a christmas tree. Their eyes are blinking irregularly, mimicking fairy lights." height="500px">

