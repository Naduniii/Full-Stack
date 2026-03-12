# Simple Social — FastAPI Image & Video Upload Application

Simple Social is a full-stack web application built with FastAPI, Streamlit, SQLite, and ImageKit. The application allows users to create accounts, upload images and videos, and view posts through a simple social-style feed.

This project demonstrates how to build a production-style backend API with authentication, database integration, and cloud-based media handling.

---

## Features

- JWT-based user authentication
- Image and video uploads
- Cloud media storage using ImageKit
- SQLite database with SQLAlchemy
- REST API built with FastAPI
- Interactive frontend built with Streamlit
- Automatic API documentation
- Media transformation and optimization using ImageKit

---

## Tech Stack

| Technology | Purpose |
|-----------|--------|
| FastAPI | Backend API framework |
| FastAPI Users | Authentication system |
| SQLite + SQLAlchemy | Database management |
| ImageKit | Image and video storage |
| Streamlit | Frontend interface |
| UV | Python dependency management |
| Pydantic | Data validation and schemas |

---

## ImageKit Integration

This project integrates ImageKit, an image and video API with AI-powered digital asset management capabilities.

ImageKit is used to handle all media operations, including:

- Uploading images and videos
- Media transformations
- Adding overlays
- Optimizing delivery
- Secure cloud storage of media files

Documentation:  
https://imagekit.io/docs

---

## Project Structure
project-root
│
├── app

│   ├── app.py

│   ├── db.py

│   ├── schemas.py

│   ├── images.py

│   └── auth.py

│
├── frontend.py

├── .env

├── pyproject.toml

└── README.md

