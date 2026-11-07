# Autocomplete System API

High-performance autocomplete and search suggestion service built with Spring Boot.

## Features
- Trie-based in-memory prefix indexing for low-latency search queries.
- RESTful endpoints for prefix query resolution and keyword ingestion.
- Configurable ranking based on search frequency and historical popularity.

## Tech Stack
- Java 21 LTS
- Spring Boot (Spring Web, Spring Data)
- Maven 3.9+

## Getting Started

### Prerequisites
- JDK 21 LTS

### Build & Run
```bash
# Build the project
./mvnw clean compile

# Run the application
./mvnw spring-boot:run
```

Server starts on port `8080` by default.
