
# TravelTracker

**TravelTracker** is a web application designed to help users log and manage the countries they've visited. Users can record their travel experiences, keep track of destinations, and categorize countries for future reference.

## Features

- Add and update the list of countries visited.
- Display countries in a categorized format.
- Store and retrieve travel data securely using PostgreSQL.
- User-friendly interface with dynamic content rendered via EJS.
- Lightweight and fast with Express.js.

---

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/) (version 14 or later)
- [PostgreSQL](https://www.postgresql.org/) (version 12 or later)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/traveltracker.git
   cd traveltracker
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the PostgreSQL database:
   - Create a new PostgreSQL database (e.g., `traveltracker`).
   - Update the database credentials in `.env` file (see Configuration).

4. Start the server:
   ```bash
   npm start
   ```

5. Open the application in your browser at:
   ```
   http://localhost:3000
   ```

---

## Configuration

Create a `.env` file in the project root with the following variables:
```env
DB_HOST=localhost
DB_USER=your_db_username
DB_PASSWORD=your_db_password
DB_NAME=traveltracker
DB_PORT=5432
PORT=3000
```

---

## Project Structure
```
TravelTracker/
├── views/                # EJS templates
├── public/               # Static assets (CSS, JS, images)
├── routes/               # Route handlers
├── models/               # Database models
├── .env                  # Environment variables
├── package.json          # Project metadata and dependencies
├── server.js             # Entry point of the application
└── README.md             # Documentation
```

---

## Dependencies

- [Express.js](https://expressjs.com/) - Fast, minimalist web framework.
- [EJS](https://ejs.co/) - Embedded JavaScript templating.
- [Body-parser](https://www.npmjs.com/package/body-parser) - Middleware for parsing incoming request bodies.
- [pg](https://node-postgres.com/) - PostgreSQL client for Node.js.

---

## Features in Development

- Search and filter countries by name or category.
- Export travel data to CSV or PDF.
- Interactive map integration to visualize visited countries.

---

## Contributing

Contributions are welcome! If you have ideas for improvement or additional features:
1. Fork the repository.
2. Create a new branch (`feature/your-feature`).
3. Commit your changes.
4. Push to your fork and create a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---
