# -hrm-office-portal
 "A comprehensive Human Resource Management system for managing civil workers' files"
# HRM Office Portal

A comprehensive Human Resource Management system for managing civil workers' files across multiple regions and offices.

## Features

- 🔐 User Authentication & Authorization (JWT)
- 👥 Civil Worker Profile Management (CRUD)
- 📁 File Upload & Storage (AWS S3)
- 🔍 Advanced Search & Filtering
- 📊 Data Export (CSV, JSON, PDF)
- 🏢 Multi-Region/Multi-Office Support
- 📝 Access Logging & Audit Trails
- 🌐 Responsive React Frontend
- ⚙️ RESTful API Backend (Express.js)
- 📦 MongoDB Database
- 🐳 Docker Containerization

## Tech Stack

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB
- **Authentication**: JWT (jsonwebtoken)
- **File Storage**: AWS S3
- **ORM**: Mongoose
- **Logging**: Winston
- **API Documentation**: Swagger/OpenAPI

### Frontend
- **Framework**: React
- **State Management**: Redux/Context API
- **HTTP Client**: Axios
- **Styling**: Tailwind CSS
- **UI Components**: Material-UI
- **Routing**: React Router
- **Form Validation**: React Hook Form

### DevOps
- **Containerization**: Docker & Docker Compose
- **Package Manager**: npm/yarn
- **Environment**: .env configuration

## Getting Started

### Prerequisites
- Node.js >= 16.x
- MongoDB >= 4.4
- AWS Account (for S3)
- Docker & Docker Compose (optional)

### Quick Start with Docker

```bash
# Clone the repository
git clone https://github.com/kanuisaiahkelvin-a11y/hrm-office-portal.git
cd hrm-office-portal

# Copy environment file
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env

# Update .env files with your configuration

# Start all services
docker-compose up -d
