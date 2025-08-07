[README.md](https://github.com/user-attachments/files/21650808/README.md)
# FSM Passport Renewal Portal

This is a full-stack web application to support the Federated States of Micronesia (FSM) passport renewal process.

## Features
- Fillable application form
- Document and photo upload
- Stripe payment integration
- Admin dashboard to manage submissions
- E-notary request feature (mockup)

## Tech Stack
- Frontend: React.js
- Backend: Node.js + Express
- Database: MongoDB (via Mongoose)
- File Uploads: Multer
- Payment: Stripe API

## Running Locally

### Frontend
```
cd frontend
npm install
npm start
```

### Backend
```
cd backend
npm install
touch .env
```

Add this to `.env`:
```
PORT=5000
MONGO_URI=your_mongodb_connection
STRIPE_SECRET_KEY=your_stripe_secret
```

Then run:
```
node server.js
```

## Deployment
- Frontend: Vercel
- Backend: Render

## License
MIT
