# 🎬 MovieApp (Ecube Website)

A **dynamic MovieApp** developed as part of the Ecube website, designed to deliver real-time movie data through an intuitive and interactive interface.  
Built using **ReactJS** for the frontend, **Node.js** for the backend, and external APIs for fetching live movie information, the app provides users with an easy way to search, view, and explore movie details.

---

## 📌 Features

- **Real-Time Movie Data**
  - Fetches movie details from an external API.
  - Displays trending, upcoming, and popular movies.

- **Search Functionality**
  - Search movies by title with instant results.

- **Movie Details Page**
  - Shows movie synopsis, release date, ratings, and cast.

- **Responsive Design**
  - Fully responsive layout for desktop, tablet, and mobile.

- **Interactive UI**
  - Smooth navigation with React Router.
  - Modern design with reusable components.

---

## 🛠 Tech Stack

**Frontend:**  
- ReactJS  
- JavaScript  
- CSS / Bootstrap  
- React Router  

**Backend:**  
- Node.js  
- Express.js  

**APIs & Data:**  
- External Movie API (e.g., TMDb API) for fetching real-time data

**Tools:**  
- VS Code  
- Git & GitHub  
- Postman (for API testing)  

---

## 📂 Project Structure

```
Ecube/
│
├── backend/           # Node.js + Express API server
│   ├── routes/        # API routes
│   ├── controllers/   # API logic
│   └── config/        # API keys and environment variables
│
├── frontend/          # ReactJS client application
│   ├── components/    # Reusable UI components
│   ├── pages/         # Pages like Home, Search, MovieDetails
│   └── services/      # API request handling
│
└── README.md
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Starplayevryr/Ecube.git
cd Ecube
```

### 2️⃣ Backend Setup
```bash
cd backend
npm install
```
- Create a `.env` file with your API key:
```
MOVIE_API_KEY=your_api_key_here
```
- Run backend:
```bash
npm start
```

### 3️⃣ Frontend Setup
```bash
cd frontend
npm install
npm start
```

---

## 📷 Screenshots

### 🎥 Demo Video
[🎥 Watch Demo Video](assets/demo.mp4)

---

## 🔮 Future Enhancements
- Add user authentication for watchlists and favorites.
- Enable movie trailer playback within the app.
- Implement advanced filtering (genre, rating, release year).

---

## 👨‍💻 Author
- **Keerthana R** ([GitHub](https://github.com/Starplayevryr))

---

## 📜 License
This project is for educational purposes and part of personal portfolio development.
