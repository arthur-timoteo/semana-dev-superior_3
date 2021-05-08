<h1 align="center">Sales analysis dashboard</h1>

<p align="center">
  <img alt="Sales analysis dashboard" src=".github/capa.png" width="100%">
</p>

## Project

Dashboard for sales analysis. We will have a CI / CD to keep the project constantly updated.

## Technologies

This project was developed with the following technologies:

- [ReactJS](https://pt-br.reactjs.org/)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [PostgreSQL 12](https://www.postgresql.org/)
- [Apexcharts](https://apexcharts.com/)

## Conceptual database model

<p align="center">
  <img alt="Conceptual database model" src=".github/sds3-mc.png" width="100%">
</p>

## Project structure

<p align="center">
  <img alt="Project structure" src=".github/camadas.png" width="100%">
</p>

## How to run

- Clone the repository;
- Access project directory;
- Access `frontend` directory;
- Install dependencies with `yarn`;
- Install the Java 11 in your machine;
- Install the STS IDE;
- Verify if the Java 11's folder is registered in the System Variables in your machine;
- To run back-end in test environment, alter variable APP_PROFILE value to `test` in the file `application.properties`;
- To run back-end in development environment, alter variable APP_PROFILE value to `dev` in the file `application.properties` and alter variables username and password values to your PostgreSQL connection data in the file `application-dev.properties`;
- To run back-end in production environment, alter variable APP_PROFILE value to `prod` in the file `application.properties` and create the environment variable DATABASE_URL in your production environment with the databse url;
- Start the back-end via the STS IDE;
- Start the front-end with `yarn start` or `npm start`

## License

This project is under the MIT license. See the [LICENSE](LICENSE.md) file for more details.