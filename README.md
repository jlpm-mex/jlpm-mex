# Hi 👋, I'm José Luis

### Software Engineer | Java · Spring Boot · React

I'm a software engineer with extensive experience designing and building backend systems and full-stack applications. I've worked on independent products from initial planning and architecture through implementation and deployment.

I enjoy solving complex engineering problems, improving existing architectures, and building maintainable software that addresses real business needs.

## Technical Focus

- **Backend:** Java, Spring Boot, REST APIs, Hibernate/JPA
- **Frontend:** React, React Native, JavaScript, TypeScript
- **Messaging & Real-Time Communication:** RabbitMQ, WebSockets
- **Databases:** MySQL, relational data modeling
- **Testing & CI/CD:** JUnit 5, Maven, GitHub Actions
- **Infrastructure:** Docker, AWS

## Featured Projects

### [Changarritos](https://changarritos.com.mx)

An independently developed platform connecting local businesses with potential customers who need their services.

I led the development from planning through backend and frontend implementation, building a system that allows customers to submit service requests and connects them with relevant businesses in the surrounding area.

**Key engineering contributions:**

- **Location-based request matching:** Customers submit a service request and select a business category. The system notifies eligible businesses in the area through email, SMS, and push notifications.
- **Asynchronous messaging:** Integrated RabbitMQ to handle notification delivery and separate business-critical notifications from transactional communications.
- **Real-time communication:** Used WebSockets to keep requests active while businesses responded, then connected the customer and the selected business through an in-app chat.
- **Configurable message templates:** Replaced hardcoded messages with a reusable template module, applying clean code principles and design patterns.
- **Architectural refactoring:** Reassessed an initial Factory/Abstract Factory implementation and replaced unnecessary complexity with a Registry/Facade-based design.
- **Dependency isolation:** Encapsulated template processing behind a dedicated service, keeping the communication management layer independent of the underlying template engine.

**Focus:** System design, asynchronous processing, real-time communication, separation of concerns, and maintainable backend architecture.

### [CFDI Admon](https://github.com/jlpm-mex/cfdiadmon)

A Java and Spring Boot project focused on managing and querying Mexican electronic invoices (CFDI).

**Focus:** Backend development, data access, and invoice data processing.

### [Java Interview Lab](https://github.com/jlpm-mex/java-interview-lab)

A collection of algorithmic problems implemented in Java, with documented approaches, complexity analysis, automated tests, and CI validation.

**Focus:** Data structures, problem-solving, testing, and code quality.

## Currently Learning

- Python programming and its ecosystem
- Machine Learning
- Software design, automated testing, and CI/CD practices

## Education

- Systems Engineering — Universidad de las Américas Puebla
- MIT Full Stack Development with MERN Certificate
- Cornell Machine Learning Certificate

## Connect

- [GitHub](https://github.com/jlpm-mex)
- [LinkedIn](https://www.linkedin.com/in/jose-luis-pino-moreno-a9a16892/)
