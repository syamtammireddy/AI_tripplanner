# 🌍 Campus Routes - AI Travel Planner

**Campus Routes** is a personalized AI-powered travel planner built using Node.js, Express.js, MongoDB, and Handlebars. Users can input their travel preferences and receive a full itinerary with hotel recommendations, day-wise activity suggestions, and more — all visually displayed and saved to their account.

---

🟢 **Live Project Link**: [Click to Visit](https://ai-trip-planner-team-7-tfzq.onrender.com)

## 🚀 Features

- 🔍 Destination input and dynamic itinerary generation using AI
- 🏨 Curated hotel recommendations
- 🗓️ Day-wise trip planner with time slots and activity details
- 📷 Image-based experience for better visual planning
- 💬 Review system for each trip
- 👤 User authentication with profile settings
- 🧳 "My Trips" section to view past itineraries

---

## 🧑‍💻 Technologies Used

- **Backend:** Node.js, Express.js
- **Frontend Templating:** Handlebars (HBS)
- **Database:** MongoDB
- **Styling:** CSS + Bootstrap
- **Image API:** Unsplash API
- **AI:** Gemini API (for generating itineraries)

---

## ✨ Screenshots

### 🧭 Trip Preferences Page
Users enter destination, trip duration, budget, and number of travelers.

![Screenshot 2025-06-29 193311](https://github.com/user-attachments/assets/d1da91e6-6ed1-40c7-ab8f-0ba95f3a966a)


---

### 📋 Generated Trip Itinerary
Dynamic page displaying the planned trip with cover image and trip summary.

![Screenshot 2025-06-29 193348](https://github.com/user-attachments/assets/54f3060f-943d-4689-974c-5b0cf6797edd)


---

### 🏨 Hotel Recommendations
AI-generated hotels with price, ratings, address, and Dynamic Google Maps links.

![Screenshot 2025-06-29 193405](https://github.com/user-attachments/assets/bab624fd-57cd-45bb-92c0-67eb6a27b43b)


---

### 📍 Places to Visit
Each day's itinerary includes locations, time slots, descriptions, and ratings.

![Screenshot 2025-06-29 193422](https://github.com/user-attachments/assets/e5dd84bd-54c0-4625-b112-33646b16f9f3)


---

### 🧳 My Trips Dashboard
User can view all saved/generated trips with cover images and metadata.

![Screenshot 2025-06-29 193444](https://github.com/user-attachments/assets/d3e49fbe-2707-4d12-a334-b371fd05f8ba)

---

### ⭐ Submit a Review
Interactive modal for rating and reviewing a trip experience.

![Screenshot 2025-06-29 193506](https://github.com/user-attachments/assets/ceca17c3-1a9c-4054-81b5-b58b6f5c3058)


---

### ⚙️ Profile Page
Users can manage their personal details, password, and see saved trips.

![Screenshot 2025-06-29 193522](https://github.com/user-attachments/assets/ab6e2f11-d1bb-43d3-8248-49152661236c)

---

## 📁 File Structure

ai-travel-planner/
├── backend/
│ ├── models/ # Mongoose schemas
│ ├── routes/ # Express route handlers
│ ├── public/ # Static assets
│ ├── views/ # Handlebars templates
│ ├── .env # Environment config
│ ├── index.js # Main server file
│ └── mongodb.js # MongoDB connection
├── README.md



---

## ✨ Features

- 🌍 Smart AI-based itinerary generation (Gemini API)
- 🏨 Hotel and activity recommendations based on user preferences
- 📷 Destination-based images using Unsplash API
- 🧾 Save & manage past trips
- 💬 Trip review & rating system
- 👤 User authentication & profile management
- 🌐 Fully responsive frontend

---

## 🧑‍💻 Tech Stack

- **Frontend Templating:** Handlebars (HBS)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **APIs:** Gemini (AI), Unsplash (images)
- **Auth:** Session-based login
- **Styling:** CSS, Bootstrap

---

## 🔧 Local Setup

```bash
git clone https://github.com/yourusername/ai-travel-planner.git
cd ai-travel-planner/backend
npm install

🛠 Add .env file with:
MONGO_URI=your_mongodb_connection_string
UNSPLASH_ACCESS_KEY=your_unsplash_api_key
GEMINI_API_KEY=your_gemini_api_key
PORT=5000

Then run:
node src/indes.js



---

✅ You can now push this `README.md` to your GitHub repo and place all screenshots in the repo root (or `assets/` folder) for visibility.


  College: IIIT Allahabad
  💼 Designation: UI Developer
