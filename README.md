# Taskboard (React + Firebase + Tailwind)

## Setup
1. `npm install`
2. Firebase Console -> new project -> add a **Web app** -> copy the config values.
3. Copy `.env.example` to `.env` and paste the values in.
4. Firebase Console -> **Authentication** -> Sign-in method -> enable **Google**.
5. Firebase Console -> **Firestore Database** -> create database.
6. Firestore -> **Rules** -> paste the contents of `firestore.rules` -> Publish.
   (First time, Firestore may ask you to create an index; if so, the browser console shows a link. Not needed for this query.)
7. `npm run dev`

## Features
- Google sign-in, each user sees only their own tasks
- Realtime sync (Firestore onSnapshot)
- Add, edit (click title), complete, delete
- Priority, due date, overdue warning
- Filters: all / active / due today / completed, plus search
- Progress bar# firebase-todo-dashboard
