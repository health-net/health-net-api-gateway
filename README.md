# Health-Net Backend API Gateway

Microservices API Gateway.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
node.js
```

### Installing

Install npm project dependencies
```
npm install
```

## Deployment

1. Set environment variables inline and start service
```
SERVICE_PORT=3000 ... npm start
```

## Details
### Environment Variables
| Name          | Description                     | Default value                                    |
|---------------|---------------------------------|--------------------------------------------------|
| HTTP_PORT     | Service port                    | 8080                                             |
| ADMIN_PORT    | Admin port                      | 9876 |
| ACCOUNT_URL | Account service url | http://localhost:2000 |
| USERS_URL | Users service url | http://localhost:3000 |
| PATIENTS_URL | Patients service url | http://localhost:4000 |
| DEVICES_URL | Devices service url | http://localhost:5000 |
