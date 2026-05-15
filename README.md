# Backend API

Simple Express + MongoDB backend for MyCheckStore.

## Setup

1. Copy `.env.example` to `.env`.
2. Update `MONGODB_URI` and `JWT_SECRET` if needed.
3. Install dependencies:
   ```bash
   npm install
   ```

## Run

- Start production server:
  ```bash
  npm start
  ```
- Start dev server with auto-reload:
  ```bash
  npm run dev
  ```

## API Endpoints 

- `GET /` - root health check
- `POST /api/auth/login`
- `POST /api/auth/register`
- `GET /api/admin`
- `GET /api/seller`
- `GET /api/contacts`
- `GET /api/orders`

## Test API
- http://localhost:3000/api/seller/profile
