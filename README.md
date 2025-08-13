# Fullstack Docker App

This is the initial folder structure for a fullstack application using **Docker**.  
The project includes separate folders for the frontend, backend, and database data.

## 📂 Project Structure

fullstack-docker-app/
│
├── backend/
│ └── Dockerfile
│
├── frontend/
│ └── Dockerfile
│
├── db-data/
│
├── docker-compose.yml
├── .env

---

This project will use **Docker** to run:
- A **React** frontend container
- An **Express** backend container
- A **PostgreSQL** database container

🗂 Planned Containers
Frontend (React)

Will run inside its own container.

Built with Dockerfile inside frontend/.

Exposes port 3000 by default.

Backend (Express)

Will run inside its own container.

Built with Dockerfile inside backend/.

Connects to PostgreSQL using environment variables.

Exposes port 5000 by default.

Database (PostgreSQL)

Uses the official PostgreSQL image.

Data will persist in db-data/ volume.

Default port 5432.

---


# Fullstack Docker App

This project uses **Docker** to run:
- A **React** frontend container
- An **Express** backend container
- A **PostgreSQL** database container with persistent data

---

🗂 Planned Containers
Frontend (React)

Built with frontend/Dockerfile.

Exposes port 3000.

Backend (Express)

Built with backend/Dockerfile.

Connects to PostgreSQL using .env variables.

Exposes port 5000.

Database (PostgreSQL)

Uses official PostgreSQL image.

Stores persistent data in db-data/ using Docker volumes.

Exposes port 5432.