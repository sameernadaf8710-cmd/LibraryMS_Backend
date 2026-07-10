# Navigate to the backend workspace
cd backend

# Ingest necessary runtime node components
npm install express mongoose jsonwebtoken bcryptjs dotenv cors

# Execute development cluster instances
node index.js

# Environment Setup
Create a .env file in the root directory:

> Code snippet

JWT_SECRET=your_super_secret_jwt_key_here

# To run in production mode
npm start

# To run in development auto-reload mode
npm run dev

# open your localhost:5000 in browser to see UI
