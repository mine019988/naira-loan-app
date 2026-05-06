# Naira Loan App - Full Stack Cloud Loan Credit Application

## Overview

A complete full-stack cloud-based loan credit application system with real-time transaction execution, automated loan disbursement, and comprehensive user verification.

### Key Features

✅ **User Verification**
- NIN/BVN validation
- Date of birth matching
- Government ID verification
- Swift approval process

✅ **Loan Management**
- Flexible loan amounts (up to ₦20,000,000)
- Real-time loan approval
- Automated disbursement to customer bank accounts
- Transaction history tracking

✅ **Payment & Transactions**
- Real-time transaction executor backend
- Bank transfer integration
- Wallet balance management
- Transaction verification & audit logs

✅ **Modern Tech Stack**
- **Frontend**: React 18 with Tailwind CSS
- **Backend**: Node.js/Express with TypeScript
- **Database**: PostgreSQL
- **DevOps**: Docker & Docker Compose
- **CI/CD**: GitHub Actions

## Quick Start

### Docker (Recommended)
```bash
docker-compose up
```

### Manual Setup
```bash
# Backend
cd backend && npm install && npm run dev

# Frontend (new terminal)
cd frontend && npm install && npm start
```

## Documentation

- [Setup Guide](documentation/SETUP.md)
- [API Documentation](documentation/API_DOCUMENTATION.md)
- [Database Schema](database/schema.sql)
- [Contributing Guidelines](documentation/CONTRIBUTING.md)

## Access Points

- 🌐 Frontend: http://localhost:3000
- 🔌 Backend API: http://localhost:5000
- 🗄️ Database: localhost:5432

## License

MIT License