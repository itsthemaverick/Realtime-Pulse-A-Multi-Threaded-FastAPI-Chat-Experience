# Realtime Pulse - A Multi-Threaded FastAPI Chat Experience

A high-performance, asynchronous real-time chat application built using FastAPI and WebSockets. Designed to handle concurrent connections efficiently using multi-threaded execution and async task processing.

## 📌 Project Overview

Realtime Pulse provides a lightweight, scalable platform for instant messaging. Key capabilities include:

* Instant, low-latency bi-directional messaging via WebSockets.

* Async and multi-threaded worker processing to handle heavy traffic.

* Room and channel creation for isolated group messaging.

* Live connection tracking and graceful disconnect handling.

## 🛠️ Key Features

1. **FastAPI & Async Engine**: Blazing fast API endpoints powered by Python's `asyncio` and ASGI standard.

2. **WebSocket Manager**: Broadcasts messages across connected clients in real-time.

3. **Multi-Threaded Tasks**: Offloads heavy processing or background tasks to thread pools.

4. **Interactive Docs**: Built-in Swagger UI for testing REST endpoints.

## 🚀 Quick Start Guide

### Prerequisites

* Python 3.9 or higher

* `pip` package manager

### Local Setup Instructions

1. **Clone the Repository**

   ```
   git clone https://github.com/itsthemaverick/Realtime-Pulse-A-Multi-Threaded-FastAPI-Chat-Experience.git
   cd Realtime-Pulse-A-Multi-Threaded-FastAPI-Chat-Experience
   
   ```

2. **Set Up Virtual Environment**

   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   
   ```

3. **Install Dependencies**

   ```
   pip install -r requirements.txt
   
   ```

4. **Run the Application**

   ```
   uvicorn app.main:app --reload
   
   ```

   Open your browser at `http://127.0.0.1:8000`.

## 📂 Project Structure

```
├── app/
│   ├── main.py            # FastAPI initialization & WebSocket routes
│   ├── connection_mgr.py  # WebSocket connection manager logic
│   ├── routes/            # API routes and WebSocket endpoints
│   └── models/            # Data models and schemas
├── requirements.txt       # Dependencies list
└── README.txt             # Project documentation

```

## 📜 License

This project is open-source and available under the MIT License.

## 👥 Author

* **Developer**: [@itsthemaverick](https://github.com/itsthemaverick)

* **Repository**: [Realtime Pulse](https://github.com/itsthemaverick/Realtime-Pulse-A-Multi-Threaded-FastAPI-Chat-Experience)
