# Project Setup Guide

## Important Branch

All active and latest development code exists in the branch:

> **temp-development**

Always switch to this branch before running or contributing to the project.

```
git checkout temp-development
```

---

## Project Structure

This repository contains both:

* Frontend
* Backend

They run separately using different commands.

---

## Installation

Clone the repository:

```
git clone <repo-url>
cd <project-folder>
```

Install dependencies for both frontend and backend:

```
npm install
```

---

## Running the Project

### 1. Start Backend

```
npm run dev
```

Backend server will start.

---

### 2. Start Frontend (Development Mode)

Open another terminal in the same project folder:

```
npm run dev
```

Frontend development server will start.

---

## Development Notes

* Always work on `temp-development` branch
* Do not push directly to main branch
* Create feature branches from temp-development if required

Example:

```
git checkout -b feature/your-feature-name
```

---

## Summary

| Service  | Command     |
| -------- | ----------- |
| Backend  | npm start   |
| Frontend | npm run dev |

---

Project is now ready to run locally.
