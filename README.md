# HR Management System - Backend

Backend API for the HR Management System developed for **INFINITY CR** and **Celulares Alex CR**.
This system streamlines administrative HR processes including employee records, attendance,
payroll, leave management, performance evaluations, and recruitment.

## Features

- **Employee Management**: digital records, personal data, contracts, job positions, work history
- **Attendance Control**: clock-in/out tracking, schedules, weekly programming, holidays
- **Leave Management**: vacations, absences, sick leave requests and approvals
- **Payroll**: income/deductions, employer contributions, annual provisions, pay receipts
- **Performance Evaluations**: evaluation criteria, results, commissions
- **Recruitment**: candidates, applications, selection pipeline stages
- **Access Control**: users, roles, and permissions
- **Notifications**: birthdays and important dates
- **Audit Log**: tracking of system actions

## Tech Stack

- **Language**: TypeScript
- **Database**: PostgreSQL (3NF)
- **Architecture**: REST API, SOLID principles, Clean Code

## Project Structure

```
src/
├── modules/        # Feature modules (employees, payroll, attendance, etc.)
├── config/         # App configuration
├── database/       # DB connection, migrations, seeds
├── shared/         # Shared utilities, middlewares, types
└── index.ts        # App entry point
```

## Getting Started

### Prerequisites

- Node.js (vXX or higher)
- PostgreSQL
- npm or yarn

### Installation

```bash
git clone <repo-url>
cd <repo-name>
npm install
```

### Environment Variables

Create a `.env` file based on `.env.example`:

```
DB_HOST=
DB_PORT=
DB_NAME=
DB_USER=
DB_PASSWORD=
JWT_SECRET=
```

### Database Setup

Run the SQL script to create the database schema:

```bash
psql -U <user> -d <database> -f database/schema.sql
```

### Run the project

```bash
# Development
npm run dev

# Production
npm run build
npm start
```

## API Documentation

API endpoints are documented at `/api/docs` (or link to Postman/Swagger collection).

## Testing

```bash
npm run test
```

## Team

- Project for: Ingeniería de Sistemas - I Ciclo 2026

## License

This project is for academic purposes.
