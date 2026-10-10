# Appointment Booking Website

An appointment booking website, with a companion admin dashboard and admin API for managing bookings.

## Overview

The project is made up of three parts that work together:

| Part | Purpose | Tech |
|---|---|---|
| **Booking website** (this repo) | Where customers book appointments | React |
| **Admin dashboard** (`appointments-admin`) | Where an admin views and manages appointments | React |
| **Admin API** (`appointments-admin-api`) | Backend that stores and serves appointment data | FastAPI, PostgreSQL |

## Features

- Online appointment booking for customers
- Admin dashboard to review and manage appointments
- REST API backed by a PostgreSQL database

## Getting started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS version recommended)
- The admin API running locally (see `appointments-admin-api`) if you want live data

### Installation

```bash
git clone https://github.com/adars-h2007/appointment.git
cd appointment
npm install
npm run dev
```

<!-- If the project was created with Create React App, use `npm start` instead of `npm run dev`. -->

Then open the local address shown in your terminal, usually `http://localhost:5173`.

### Build for production

```bash
npm run build
```

## Tech used

- React (frontend)
- FastAPI (admin API)
- PostgreSQL (database)

## Roadmap

- [ ] Email or SMS confirmations for bookings
- [ ] Time-slot availability and conflict checks
- [ ] Admin login and roles

## Author

**Adarsh Patil**

- GitHub: [@adars-h2007](https://github.com/adars-h2007)
- LinkedIn: [Adarsh Patil](https://www.linkedin.com/in/adarsh-patil-587a65319/)
- Email: adarshpatil6650@gmail.com
