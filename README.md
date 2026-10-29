# Volunteera

Volunteera is a University of Surrey COM2027 group project: a web application designed to connect volunteers with charities and organisations seeking help with social causes.

The repository contains the work of Group 7: Alex Morris, William Rodriguez-Ward, Thomas Fitzsimons, Adel Anarbayeva, Rudhr Shaji, Dzak Dzulzalani and Dylan Farrar.

## What the application includes

- Volunteer and organisation registration and profiles.
- Browsing volunteering opportunities, applications and opportunity discussions.
- Organisation tools for creating opportunities and managing applications.
- Volunteer interests, friendships, badges and a leaderboard.

These describe the functionality represented in the repository; this is a coursework project and the current deployment or service availability has not been verified.

## Technology

- **Frontend:** React, React Router, Vite and Tailwind CSS.
- **Backend:** Python, Django, Django REST Framework and Django Channels.
- **Infrastructure:** Docker Compose, Redis, Daphne and nginx.

## Repository layout

- `frontend/` — React application.
- `backend/` — Django models, views and API routes.
- `volunteermatch/` — Django project configuration.
- `docker-compose.yml` and `Dockerfile.*` — container configuration.

## Running the project

The repository includes a Docker Compose configuration:

```sh
docker compose up --build
```

The configured frontend and backend ports are 5000 and 8000 respectively. This historical coursework configuration has not been retested; external services, credentials and environment settings may need updating for a local setup. Review the configuration before deploying it.

## Project context

The original [group project metadata](com2027.yml) describes Volunteera as supporting social causes associated with good health and wellbeing and reduced inequalities.
