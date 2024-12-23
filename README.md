# Full-Stack WhatsApp Clone

A WhatsApp clone built with some of the latest and most efficient technologies of 2024! This project leverages **Spring Boot 3**, **Angular 18**, **PostgreSQL**, **Keycloak**, **Bootstrap**, **Liquibase**, and **Docker** to create a modern, scalable, and secure messaging application.

## Key Features
- 💬 **Real-time messaging**: Experience seamless communication.
- 👥 **Conversations management**: Organize and manage chats effectively.
- 📁 **File sharing**: Share images, videos, and documents.
- 🔐 **Authentication and Authorization**: Secure access with Keycloak (OAuth2) and role management.
- 🏢 **Hexagonal architecture**: Ensures maintainable and modular codebase.

## Technologies Used
- **Backend**: Spring Boot 3
- **Frontend**: Angular 18
- **UI Framework**: Bootstrap
- **Database**: PostgreSQL
- **Authentication**: Keycloak
- **Version Control**: Liquibase
- **Containerization**: Docker

By the end of this project, you'll gain a deeper understanding of creating a full-stack application from scratch and be equipped to tackle similar large-scale projects using modern technologies.

---

## Project Setup

### Backend

### Prerequisites
- [JDK 21](https://adoptium.net/temurin/releases/)
- [PostgreSQL](https://www.postgresql.org/download/)
- IDE ([IntelliJ](https://www.jetbrains.com/idea/download/))
- Docker ([Docker Desktop](https://docs.docker.com/engine/install/))

#### Clone the Repository
```bash
git clone https://github.com/Bahri-Adem/Full-Stack-WhatsApp-Clone-SpringBoot-3-Angular-18-PostgreSQL-Keycloak-Bootstrap.git
cd Full-Stack-WhatsApp-Clone-SpringBoot-3-Angular-18-PostgreSQL-Keycloak-Bootstrap/Backend
```

#### Run Keycloak and PostgreSQL Containers
Use Docker Compose to start the required services:
```bash
docker-compose -f src/main/docker/keycloak.yml up -d
docker-compose -f src/main/docker/postgres.yml up -d
```
---

### Frontend

#### Prerequisites
- [NodeJS 20.11 LTS](https://nodejs.org/dist/v20.11.1/node-v20.11.1.pkg)
- [Angular CLI v18](https://www.npmjs.com/package/@angular/cli)
- IDE ([VSCode](https://code.visualstudio.com/download))

#### Setup and Launch
Fetch dependencies:
```bash
npm install
```

Start the development server:
```bash
ng serve
```

Navigate to [http://localhost:4200/](http://localhost:4200/). The application will automatically reload if you change any source files.

---

## Project Structure

- **Backend**: Contains the Spring Boot application following Hexagonal architecture.
- **Frontend**: Built with Angular 18 and Bootstrap for a responsive UI.
- **Docker**: Contains configuration files for running Keycloak and PostgreSQL in containers.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contributions
Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

---

## Author
**Adem Bahri**
- GitHub: [Bahri-Adem](https://github.com/Bahri-Adem)
- LinkedIn: [Adem Bahri](https://www.linkedin.com/in/adem-bahri/)
