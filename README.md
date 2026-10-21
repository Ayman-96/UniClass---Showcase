# UniClass

A study platform where students of a class share knowledge and questions directly inside the lecture PDF.

**Live demo:** [uni-class.vercel.app](https://uni-class.vercel.app/)

> The source code for this project is private. This repo is a showcase of what it does and how it is built.

## The problem

Class discussions are scattered across chat groups, and questions about a specific slide get lost. UniClass puts the conversation on the slide itself, so every question and answer stays attached to the lecture it is about.

## Features

- **Accounts:** sign up, sign in, password reset, and a first-time setup flow
- **Class groups:** each group has its own courses, posts, members, announcements, and settings
- **Course workspaces:** lectures for each course in one place
- **Lecture PDF viewer:** read lectures inside the app
- **Per-slide discussions:** ask and answer questions on a specific slide
- **Private notes:** write notes only you can see
- **Notifications:** updates delivered in real time
- **Classmates and profile:** find classmates and manage your own profile and settings
- **PDF download:** save any lecture for offline study

## Tech stack

| Area | Tools |
| --- | --- |
| Frontend | React, React Router, Vite |
| PDF viewing | react-pdf (PDF.js) |
| Backend and database | Supabase |
| Server state | React Query |
| Client state | Zustand |
| Icons and notifications | Lucide, Sonner |

## What I learned

- Setting up a Supabase database and connecting it to a React app
- Managing server data with React Query, including cache updates after changes
- Separating server state (React Query) from UI state (Zustand)
- Rendering PDFs in the browser and attaching discussions to individual slides

## Author

**Ayman Hardy Jawad**, Software & Informatics Engineering student at the University of Salahaddin, Erbil.

[GitHub](https://github.com/Ayman-96)
