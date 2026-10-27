# Vehicle Parking Reservation

A full-stack parking reservation web app built with the Next.js App Router, TypeScript and MongoDB.

## Tech Stack

- **Framework:** Next.js 15 (App Router), React 19, TypeScript
- **UI:** Material UI (incl. Data Grid), Tailwind CSS 4, react-toastify
- **Database:** MongoDB with Mongoose models
- **Auth:** JWT-based authentication with bcrypt password hashing and cookie sessions
- **Email:** Nodemailer
- **HTTP:** Axios

## Project Structure

```
src/
  app/
    (Auth)/      sign-in and sign-up flows
    (Private)/   authenticated pages
    (Public)/    public pages
    api/         route handlers
  components/    reusable UI
  dbModels/      Mongoose schemas
  services/      API client layer
  hooks/ lib/ utils/ types/ config/
```

## Getting Started

```bash
yarn install
yarn dev      # http://localhost:3000
```

Create a `.env.local` with your MongoDB connection string, JWT secret and SMTP settings before running.
