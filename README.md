# CMPT 315 - Lab 11

## How to Run

### 1. Install dependencies
From project root:
```bash
npm install
cd server && npm install
cd ../client && npm install
```

### 2. Set environment variables
Create `server/.env` with:
```
MONGODB_URI=your_mongodb_uri
SESSION_SECRET=your_secret
PORT=5001
NODE_ENV=development
```

### 3. Run in development
Backend:
```bash
cd server
node server.js
```

Frontend (new terminal):
```bash
cd client
npm run dev
```

Open:
```
http://localhost:5173
```

### 4. Run production build
From root:
```bash
npm run build
npm start
```

Open:
```
http://localhost:5001
```

### 5. Test login
```
username: student
password: password123
```
