# My Bidhaa Marketplace

A full-stack e-commerce marketplace platform built with React.js, Node.js, Express, and MySQL.

## Features

- User authentication (signup/login)
- Product catalog with categories
- Search and filter functionality
- Shopping cart
- Seller dashboard
- Order management
- Product reviews and ratings
- Secure payment integration

## Tech Stack

- **Frontend**: React.js, Material-UI, Redux
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Authentication**: JWT
- **File Upload**: Multer
- **API Security**: CORS, Helmet

## Project Structure

```
bidhaa-marketplace/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── redux/
│       └── services/
├── server/                 # Node.js backend
│   ├── config/
│   ├── controllers/ 
│   ├── middleware/
│   ├── models/
│   └── routes/
└── uploads/               # Product images storage
```

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   cd client && npm install
   ```
3. Create a `.env` file in the root directory with:
   ```
   DB_HOST=localhost
   DB_USER=your_username
   DB_PASSWORD=your_password
   DB_NAME=bidhaa_db
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```
4. Set up the MySQL database:
   - Create a database named 'bidhaa_db'
   - Run the SQL scripts in `server/config/database.sql`

5. Start the development servers:
   ```bash
   # Run backend and frontend concurrently
   npm run dev:full
   ```

## API Documentation

The API documentation can be found in the `/docs` directory.

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request 