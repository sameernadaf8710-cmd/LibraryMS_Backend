<img width="1600" height="758" alt="WhatsApp Image 2026-07-10 at 3 14 28 PM" src="https://github.com/user-attachments/assets/f8912b89-1a44-4940-97d3-b2f6f9d4f71c" />
<img width="1175" height="640" alt="Screenshot 2026-07-10 151707" src="https://github.com/user-attachments/assets/5a8ac3b3-636e-447f-aedb-7aedd2cf5247" />
<img width="1161" height="688" alt="Screenshot 2026-07-10 151640" src="https://github.com/user-attachments/assets/73ab00cc-3f94-4002-81a1-cd55b3aec6f3" />
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
