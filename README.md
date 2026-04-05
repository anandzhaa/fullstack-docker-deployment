# Full Stack Deployment using Docker, CI/CD & Monitoring

## Objective
Deploy a full-stack application using Docker on a VM with CI/CD and monitoring.

## Tech Stack
- Frontend: React (Docker)
- Backend: Node.js (Docker)
- Database: MongoDB (Docker)
- CI/CD: GitHub Actions
- Monitoring: Prometheus & Grafana

## Setup Instructions

### Run Application
docker compose up -d --build

### Access Application
Frontend: http://localhost:8080  
Backend: http://localhost:3000  

### Monitoring
Prometheus: http://localhost:9090  
Grafana: http://localhost:3001  

## Monitoring Details
- Node Exporter collects system metrics
- Prometheus collects data
- Grafana visualizes CPU & Memory usage

## CI/CD
- Auto deployment using GitHub Actions on push to main branch
- Uses SSH key and secrets for secure deployment

## Failure Testing
- Backend container stopped and restarted
- Application successfully recovered

## Conclusion
Successfully deployed and monitored a full-stack application using Docker and CI/CD pipeline.

