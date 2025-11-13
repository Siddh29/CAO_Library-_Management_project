📚 Smart Library Management System
Automated Book Sorting + Path Optimization using RFID, Node.js, SQLite & Next.js

This project is a Smart Library Management System that automates the arrangement of books and calculates the minimum path required to sort books efficiently.
The system is designed to work with RFID-tagged books, providing near real-time tracking, optimized sorting steps, and visual insights into book arrangement.

🚀 Features
🔍 Book Management

Add, update, delete books

Live list of all books

Auto-generated RFID codes

Book categories, author, ISBN support

🗺️ Path Optimization

Calculates minimum walking distance required to place each book into its correct shelf and position

Step-by-step optimized sorting session

Cumulative distance tracking

⚡ Database Tools

Seed Database with 120 random + real book titles

Reset Database

Fast local SQLite (using better-sqlite3)

Auto-migration for new fields (e.g., RFID column)

🎨 UI/UX

Modern interface using Next.js App Router

Dark/Light Mode with LocalStorage persistence

Stats dashboard

Clean book list

Responsive layout

🛠️ Tech Stack
Frontend

Next.js 14 (App Router)

React + Hooks

TailwindCSS

Lucide Icons

Backend

Node.js

Next.js API Routes

better-sqlite3 (high-performance local DB)

Database

SQLite

Auto migrations + indices


🔮 Future Improvements

RFID Scanner Integration

Real-time book tracking

Heatmaps for walking paths

Multi-user authentication

Drag & drop shelf mapping
