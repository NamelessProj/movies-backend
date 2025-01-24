# Movies Backend
This is the backend part of the Movies application build in java.

The frontend part can be found [here](https://github.com/NamelessProj/movies-frontend).

## Installation
1. Clone the repository
2. Run `mvn clean install` to build the project
3. Run `mvn spring-boot:run` to start the application
4. The application will be available at `http://localhost:8080`

## Environment variables
In the [`.env.exemple`](/src/main/resources/.env.example) file you can find the environment variables that need to be set in order to run the application.

The `.env` file should be placed in the `src/main/resources` folder and looks like this:
```env
MONGO_DATABASE="your-database-name"
MONGO_USER="your-username"
MONGO_PASSWORD="your-password"
MONGO_CLUSTER="your-cluster"
```