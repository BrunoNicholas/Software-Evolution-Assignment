<h1 class="width: 100%; text-align: center;">Software-Evolution-Assignment</h1>

This is to describe the topic for the Inventory Management System

# 📦 Inventory Management System
 
## Project Description
 
The Inventory Management System is a robust application designed to help businesses track, manage, and optimize their stock levels in real time. It provides a centralized platform for monitoring product quantities, managing suppliers, processing stock movements, and generating insightful reports — reducing manual errors and improving operational efficiency.
 
Whether you're running a small retail shop or managing a large warehouse, this system scales to meet your needs with an intuitive interface and powerful backend.
 
---

## Installation Instructions
 
### Prerequisites
 
Before getting started, ensure you have the following installed:
 
- [Node.js](https://nodejs.org/) v18 or higher
- [npm](https://www.npmjs.com/) v9 or higher
- [PostgreSQL](https://www.postgresql.org/) v14 or higher
### Steps
 
1. **Clone the repository to your computer to create the project folder with the its files**
```bash
   git clone https://github.com/BrunoNicholas/Software-Evolution-Assignment.git
   cd inventory-system
```
 
2. **Install dependencies from the packages script**
```bash
   npm install
```
 
3. **Configure environment variables**
   Copy the example env file and update it with your settings:
```bash
   cp .env.example .env
```
 
   Open `.env` and fill in the required values:
 
```env
   DB_HOST=localhost
   DB_PORT=5432
   DB_NAME=inventory_db
   DB_USER=your_db_user
   DB_PASSWORD=your_db_password
   PORT=3000
```
 
4. **Run database migrations**
```bash
   npm run migrate
```
 
5. **Start the application**
```bash
   npm start
```
 
   The app will be available at `http://localhost:3000`.
 
---
 
## Usage Instructions
 
### Running in Development Mode
 
```bash
npm run dev
```
 
This starts the server with hot-reloading enabled for a smoother development experience.

### Core Features
 
- **Add Products** — Navigate to `Products > Add New` to register new inventory items with details such as name, SKU, category, and quantity.
- **Update Stock** — Use `Stock > Adjust` to record incoming or outgoing stock movements.
- **View Reports** — Go to `Reports > Overview` to see low-stock alerts, stock valuation, and movement history.
- **Manage Suppliers** — Under `Suppliers`, add and link suppliers to your product catalog.
### Running Tests
 
```bash
npm test
```
 
---
 
## Contributors
 
We appreciate all the individuals who have contributed to making this project possible!
 
| Name | Role | GitHub |
|---|---|---|
| Bruno Nicholas Sserunkuma | Project Lead & Backend Engineer | [@brunonicholas](https://github.com/brunonicholas) |
|  |  |  |
 
Want to contribute? Fork the repo, make your changes, and open a pull request. Contributions, bug reports, and feature requests are always welcome!
 
---
 
*Built with ❤️ by the Bruno Nicholas Sserunkuma*