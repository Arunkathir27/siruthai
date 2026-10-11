# Siruthai - Simple Calendar App

A full-stack calendar application with Express.js backend and vanilla JavaScript frontend.

## Features

- View calendar for any month
- Add, edit, and delete events
- Event persistence with backend API
- Responsive design

## Project Structure

```
├── backend/          # Express.js API server
│   ├── server.js
│   ├── package.json
│   └── routes/
│       └── events.js
├── frontend/         # HTML/CSS/JavaScript
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── app.js
└── README.md
```

## Quick Start

### Backend Setup

```bash
cd backend
npm install
npm start
```

Server runs on `http://localhost:3000`

### Frontend Setup

1. Open `frontend/index.html` in your browser
2. Or run with a local server:

```bash
cd frontend
python -m http.server 8000
# or
npx http-server
```

Access at `http://localhost:8000`

## API Endpoints

- `GET /api/events` - Get all events
- `GET /api/events/:date` - Get events for a specific date
- `POST /api/events` - Create a new event
- `PUT /api/events/:id` - Update an event
- `DELETE /api/events/:id` - Delete an event

## Technologies Used

- **Backend**: Node.js, Express.js, CORS
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Data**: In-memory storage (easily extensible to database)
