# MediQueue

MediQueue is a smart mobile application designed to simplify appointment booking and queue management for clinics and hospitals. It allows patients to book appointments, track their live position in the queue, and receive timely notifications. On the clinic side, it helps staff and doctors manage appointments and patient flow efficiently.

## Core Features

- Appointment booking with real-time queue tracking
- Live queue dashboard for clinic staff to manage patients
- Patient check-in via app or QR code scan
- Real-time notifications about queue status and delays
- Multi-language support (English and Nepali)
- Wait time estimation based on queue position and average consultation time
- Clinic locator map showing nearby clinics with details and booking options
- Hybrid queue management with manual and automatic progression

## Patient Side (Mobile App Client)

- Developed using **Flutter** for a smooth, mobile-first experience
- Supports appointment booking, live queue updates, notifications, and multi-language
- Includes clinic map locator and patient check-in features

## Clinic Side (Admin Dashboard)

- Backend interfaces accessible via web or mobile
- Allows doctors and staff to manage schedules, queues, and appointments
- Provides patient information and queue control tools

## Technologies Used

- **Frontend (Patient):** Flutter (Dart) for a smooth, mobile-first experience  
- **Backend API:** FastAPI (Python) for handling real-time updates and REST endpoints  
- **Notifications & Utilities:** Node.js for managing notification services and other utilities  
- **Database:** PostgreSQL for production and SQLite for development/testing  
- **Real-time Updates:** WebSockets implemented via FastAPI  
- **Hosting:** Render for backend services, Firebase or App Stores for mobile app distribution  


