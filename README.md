# Totem Fast Food JK Burguer

Totem Fast Food JK Burguer is a self-service fast food kiosk system developed as a full stack academic product with a Spring Boot backend and a React frontend.

The project was designed to simulate a real ordering experience, allowing customers to browse products, assemble orders, choose payment methods, and interact with a loyalty flow based on CPF.

## Overview

| Area | Description |
| --- | --- |
| Problem | Fast food ordering can create queues, manual errors, and a slower customer flow. |
| Solution | A self-service kiosk experience with menu browsing, cart, checkout, payment options, and loyalty flow. |
| Focus | Full stack development, REST API integration, business flow modeling, and customer experience. |
| Status | Academic project completed and kept as portfolio proof of full stack product construction. |

## Project Goal

The main goal of this project is to model a digital self-service experience for the food business, reducing queues, improving customer flow, and organizing the purchase process in a more efficient way.

This project is important in my portfolio because it connects software development with real business operations, customer experience, and retail process design.

## Main Features

- Digital menu browsing.
- Product and combo selection.
- Cart with quantity and order summary.
- CPF-based loyalty flow.
- Payment options such as Pix, debit, and credit.
- Simplified receipt flow.
- Frontend and backend separated by API.

## Tech Stack

### Backend

- Java 21
- Spring Boot
- Spring Data JPA
- MySQL

### Frontend

- React
- React Router
- JavaScript

### Project Support

- Git and GitHub
- Jira for task and sprint organization

## Architecture

```text
React Frontend
    -> REST API
Spring Boot Backend
    -> Spring Data JPA
MySQL Database
```

## Business Context

This project represents more than a technical implementation. It simulates a business scenario where technology supports sales flow, loyalty strategy, customer interaction, and operational efficiency.

It reflects the kind of product I enjoy building: systems that connect technology, execution, process, and business value.

## Repository Structure

```text
backend-totem/
Totem/
README.md
```

## Running Locally

### Prerequisites

- Java 17 or higher.
- Node.js
- MySQL 8
- Maven

### Backend

```bash
cd backend-totem
mvn spring-boot:run
```

Configure the local MySQL database according to the backend application properties before running the API.

### Frontend

```bash
cd Totem
npm install
npm run dev
```

## Portfolio Notes

- Demonstrates a business-oriented full stack flow.
- Shows API integration between frontend and backend.
- Practices data modeling for products, orders, payments, and customer interaction.
- Connects software development with retail operation and customer experience.

## Status

Academic project completed and kept as portfolio proof of full stack product construction.

## Author

John Kevin

- GitHub: [JohnKevinDevs](https://github.com/JohnKevinDevs)
- LinkedIn: [john-kevin-alves](https://www.linkedin.com/in/john-kevin-alves/)
