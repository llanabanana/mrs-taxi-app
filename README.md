# MRS Taxi App

A full-stack ride-sharing platform developed as a team project for the Software Engineering in Information Technologies (SIIT) course at the Faculty of Technical Sciences, University of Novi Sad.

This is a fork of the original team repository ([kzi-nastava/mrs-team6-team123](https://github.com/kzi-nastava/mrs-team6-team123)).

## About

The application simulates a taxi service similar to Uber or Bolt. It supports three user roles -- passengers, drivers, and administrators -- each with dedicated functionality. Key features include ride ordering with route selection on a map, real-time ride tracking, driver assignment, in-app chat, ride history and reports, panic alerts, user registration and profile management, and an admin dashboard.

The project was developed using Scrum/Agile methodology across multiple sprints, with the team collaborating through GitHub pull requests and code reviews.

## Tech Stack

- **Backend**: Java 17, Spring Boot 4, Spring Security, Spring Data JPA, H2 (test), Springdoc OpenAPI
- **Frontend**: Angular 21, TypeScript
- **Mobile**: Android (Java, Gradle, min SDK 30)
- **Testing**: JUnit, Selenium, Karma

## Project Structure

```
Projekatsiit2023/   - Spring Boot backend (REST API)
client-layer/       - Angular web frontend
mobile-application/ - Android mobile app for drivers
```

## Running the Project

**Backend**

```bash
cd Projekatsiit2023/Projekatsiit2023
./mvnw spring-boot:run
```

**Frontend**

```bash
cd client-layer
npm install
ng serve
```

The web app runs at `http://localhost:4200/`.

**Mobile**

Open the `mobile-application/` directory in Android Studio and run on an emulator or device.

## Team

This was a collaborative university project. Contributors can be found in the commit history.
