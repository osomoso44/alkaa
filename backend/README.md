# Alkaa Backend

Backend server for Alkaa application built with Ktor.

## Development

### Prerequisites
- JDK 17 or higher
- Gradle 8.0 or higher

### Running locally
```bash
./gradlew run
```

The server will start on `http://localhost:8080`

### Building
```bash
./gradlew build
```

## Deployment

This project is configured for deployment on Railway.

### Railway Deployment
1. Create a new project on Railway
2. Connect your GitHub repository
3. Railway will automatically detect the configuration and deploy

### Environment Variables
- `PORT`: The port the server will run on (default: 8080)

## API Endpoints

### Health Check
- `GET /health`: Returns 200 OK if the server is running

## License
MIT 