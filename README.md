# Weekly Team Log (Jun 10 – Jun 16, 2025)

---

## Date Range  
- 2025-06-10 (Tue) – 2025-06-16 (Mon)

---

## Features in the Project Plan Cycle  
- Frontend scaffold & routing (Vite+TS + React Router with protected routes)  
- Backend admin UI setup (Django Admin model registration)  
- Dashboard & team-log ownership handoff  
- Continuous PR review & merge process  

---

## Associated Tasks from Project Board  

| Task ID | Description                                                    | Feature                  | Assigned To         | Status      |
|:-------:|----------------------------------------------------------------|--------------------------|---------------------|-------------|
| #148    | Initialize React App using Vite + TypeScript                   | Frontend Setup           | Richard Pillaca     | Complete    |
| #149    | Set Up React Router with Protected Routes                      | Frontend Routing         | Richard Pillaca     | Complete    |
| #150    | Set Up Axios instance with JWT for frontend–backend comms      | API Integration          | Richard Pillaca     | Complete    |
| #151    | Create Instructor Dashboard UI (no logic)                      | Dashboard Implementation | Team Member A       | In Progress |
| #152    | Create Login Page UI (no logic)                                | Dashboard Implementation | Team Member B       | In Progress |
| #153    | Register models from all apps in Django Admin                  | Backend Admin UI         | Richard Pillaca     | In Progress |
| #154    | Review & merge outstanding pull requests                       | Process                  | All Team            | Ongoing     |

---

## Tasks for Next Cycle  

| Task ID | Description                                                    | Est. Time (hrs) | Assigned To      |
|:-------:|----------------------------------------------------------------|-----------------|------------------|
| #153    | Finish Django Admin model registration (filters, titles)       | 4               | Richard Pillaca  |
| #155    | Build core React Dashboard components (with logic)             | 8               | Team Member A    |
| #156    | Draft “Developer Setup” guide (Docker + React + Django)        | 3               | Team Member C    |
| #157    | Finalize `.env`-based config for dev/prod environments         | 2               | Team Member D    |

---

## Burn-up Chart (Velocity)  

![image](https://github.com/user-attachments/assets/b1ba92a9-5804-4e44-89d5-1b5d0c3f91a9)


## 4. Burn-up Chart (Overall Progress)
![burnUpFriday_week5](https://github.com/user-attachments/assets/58bf1325-1ab2-41f0-a4ba-ea8b362f5070)


---


> **Open:** green, **Completed:** purple, **Duplicates:** grey

---

## Team Hours  

| Team Member           | Logged Hours |
|-----------------------|--------------|
| Richard Pillaca       | 6h 15m       |
| Jeff Paller           | 5h 30m       |
| Jeel Patel            | 5h 00m       |
| Leia Treacher         | 4h 45m       |
| Abdullah Alkaf        | 4h 00m       |
| Jaitra Patel          | 4h 15m       |

> *Daily 30-minute syncs; ad-hoc reviews as needed.*

---

## Completed Tasks  

| Task ID | Description                                         | Completed By      |
|:-------:|-----------------------------------------------------|-------------------|
| #148    | React + Vite scaffold                               | Richard Pillaca   |
| #149    | React Router with protected routes                  | Richard Pillaca   |
| #150    | Axios + JWT setup for API calls                     | Richard Pillaca   |
| #157    | CORS headers & pgAdmin in Docker                    | Richard Pillaca   |

---

## In Progress / To-Do  

| Task ID | Description                                         | Assigned To      |
|:-------:|-----------------------------------------------------|------------------|
| #151    | Instructor Dashboard UI (no logic)                  | Team Member A    |
| #152    | Login Page UI (no logic)                            | Team Member B    |
| #153    | Django Admin model registration                     | Richard Pillaca  |
| #154    | Ongoing PR review & merges                          | All Team         |

---

## Test Report / Status  
- **Health-check endpoints:** all core services return 200 at `/health/`.  
- **Auth (manual via Postman):** JWT issuance, refresh, and invalid-credential handling verified.  
- **Exams endpoint security:** accessible only to authenticated users.  
- **Automated tests:**  
![image](https://github.com/user-attachments/assets/dfcd7c49-16b7-4438-bab9-ee5a4acc9c70)
