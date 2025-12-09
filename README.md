## Uniride
Uniride is a web-based smart mobility system designed to eliminate long queues, unpredictable wait times, and transport congestion within university campuses. It provides real-time updates on bus availability, queue length, seat count, and arrival times, allowing students to move across campus efficiently. while giving school authorities full oversight of transport operations.


# 🎯 Problem Statement

Students across Nigerian tertiary institutions face significant delays at transport parks, often waiting for hours due to poor coordination between buses, drivers, and routes. This leads to:

- Missed classes, tests, and exams
- Physical stress and safety concerns
- Congestion at campus parks
- Zero data for administrators to plan bus allocation

With many universities still operating manually, there is no reliable way for students to know:

- How many buses are available
- Estimated arrival times
- Queue position
- Which park is moving faster
- Which route has capacity
- Uniride solves this problem using real-time digital coordination.

# 🚀 Solution Overview

Uniride is a web application + PWA that students can install on their phones like a native app.
It includes three main modules:

> 1. Student App

- View available buses per park
- See estimated waiting time
- Join queue digitally
- Track queue position
- Receive notifications when it’s almost their turn
- View bus routes and seat availability

> 2. Driver App

- Mark arrival at a park
- Update seat availability
- Mark departure
- Select route and destination
- Automated logs for admin reporting

> 3. Admin Dashboard

- Monitor queues in real time
- Track bus movement, capacity, and load
- See traffic trends and peak periods
- Allocate buses efficiently based on data
- Generate transport reports and analytics

# 🛠️ Technology Stack
**Frontend**
- React (Vite)
- TailwindCSS
- Progressive Web App (PWA) features
- Socket.IO client (real-time updates)

**Backend**

- Node.js (Express)
- Socket.IO (real-time communication)
- PostgreSQL (primary database)
- Redis / Memurai (queue caching & fast state sync)
- JWT authentication
- Infrastructure (Planned)
- Nginx reverse proxy
- Cloud hosting (Render, Railway, AWS, or Azure)
- CI/CD for deployments

# 📡 Core Features (v1)

- Real-time queue updates
- Digital park selection
- Park congestion overview
- Bus arrival/departure tracking
- Driver-to-student live sync
- Admin analytics
- PWA installation for mobile-app-like experience

# 📑 Project Structure
```bash
uniride/
│
├── uniride-frontend/   # React + Tailwind + PWA
└── uniride-backend/    # Node.js + Express + Socket.IO
```

Each module is developed independently and communicates through REST + WebSockets.

# 🧪 Current Status

- Project planning ✔️
- Technical architecture draft ✔️

- Backend scaffolding underway
- Frontend setup initialized
- Database schema design in progress

# 🎯 Target Impact

Uniride aims to:

- Reduce average student waiting time by 60–80%
- Provide data-driven transport management for campuses
- Improve safety and movement efficiency
- Serve as a scalable solution for universities across Nigeria

# 🧩 Long-Term Vision

After deployment in one institution, Uniride will expand to:

- Multi-campus support
- GPS-enabled bus tracking
- In-app payment for bus fares
- Predictive transport analytics
- Licensing model for universities

# 👥 Team Structure

- Lead Developer (Frontend + Backend)
- UI/UX Designer
- Backend/Database Engineer
- Business Analyst
- Academic Mentor/Supervisor
