# Dockeriza_MERN_Stack_App2
# Dockeriza_MERN_Stack_App2



# Dockerized MERN Stack Application

## Project Overview
A full-stack web application built with MongoDB, Express.js, React.js, and Node.js, containerized using Docker for consistent development and deployment.

## Prerequisites
- Docker
- Docker Compose
- Node.js (optional, for local development)

## Project Structure
```
.
├── backend/
│   ├── Dockerfile
│   └── package.json
├── frontend/
│   ├── Dockerfile
│   └── package.json
├── docker-compose.yml
└── README.md
```

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/edrisselminiar/Dockeriza_MERN_Stack_App2
cd Dockeriza_MERN_Stack_App2
```

### Environment Configuration
1. Create `.env` files in backend and frontend directories
2. Configure necessary environment variables

### Build and Run
```bash
# Build docker containers
docker-compose build

# Start the application
docker-compose up
```

### Accessing the Application
- Frontend: `http://localhost:3000`
- Backend API: `http://localhost:5000`
- MongoDB: `mongodb://localhost:27017`

## Development Workflow
- Make changes to source code
- Docker will automatically rebuild and restart services
- Use `docker-compose down` to stop services

## Docker Services
- `frontend`: React.js application
- `backend`: Node.js/Express.js server
- `mongodb`: Database storage

## Deployment
Modify `docker-compose.yml` for production:
- Add volume mounts
- Configure network settings
- Set production environment variables

## Troubleshooting
- Ensure Docker is running
- Check container logs: `docker-compose logs`
- Rebuild containers: `docker-compose build --no-cache`

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Containerization**: Docker, Docker Compose

## License
[Specify your license]
```
# Dockeriza_MERN_Stack_App2
