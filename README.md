# Book Tracker Frontend

A flexible and reusable frontend for a Book Tracking and Note Sharing App, built with Next.js, TailwindCSS, Zustand, React Hook Form, Zod, and React Hot Toast.
Users can create accounts, track their books, write notes, and choose whether to make their notes private or public to share with others.

## Tech Stack

* Next.js – React framework for building scalable web applications
* TailwindCSS – Utility-first CSS framework for styling
* Zustand – Lightweight state management
* React Hook Form – Form management and validation
* Zod – Schema validation for forms
* React Hot Toast – Toast notifications for UI feedback
* Axios – HTTP client for API calls

## Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/Meriemchm/chm_next_book_tracker_website.git
cd chm_next_book_tracker_website
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a **`.env`** file in the root directory and add the following:

```
NEXT_PUBLIC_API_URL=https://chm-book-tracker-backend.onrender.com/api
```

* `NEXT_PUBLIC_API_URL`: Base URL for the backend API

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the frontend.

## Features

* Global modal system using Zustand
* Animated components with GSAP
* Form validation with React Hook Form + Zod
* Toast notifications with React Hot Toast
* API integration with Axios
* Responsive UI with TailwindCSS

## Folder Structure

```
src/
 ├── app/            → Next.js pages and layout
 ├── components/     → Reusable UI components
 ├── hooks/          → Custom hooks (e.g., GSAP animations)
 ├── store/          → Zustand stores for global state
 ├── schemas/        → Zod schemas for form validation
 └── lib/            → utilities
```

## Usage

* Use Zustand stores to manage global state like modal visibility, user session, and book data.
* Use React Hook Form + Zod for all form handling and validation.
* Use Axios to communicate with the backend API.
* Use React Hot Toast for feedback messages on user actions.

## Running the App

Start the development server:

```bash
npm run dev
```

Visit [coming soon](coming soon) to explore the Book Tracker frontend.
