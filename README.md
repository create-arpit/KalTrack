# KalTrack
Calorie Tracker (MERN) MERN‑stack app to log meals, track calories via API, and view charts.


git clone https://github.com/yourname/calorie-tracker.git
cd calorie-tracker
npm install
cd client && npm install
cd ../server && npm install
Create .env in server/:

ini
Copy
Edit
PORT=5000
MONGO_URI=<your MongoDB URI>
JWT_SECRET=<your secret>
NUTRITION_API_KEY=<nutrition API key>
Create .env in client/:

bash
Copy
Edit
REACT_APP_API_BASE_URL=http://localhost:5000/api
Start everything:

bash
Copy
Edit
cd ..
npm run dev
