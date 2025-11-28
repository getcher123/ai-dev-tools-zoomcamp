# Django TO-DO App

A lightweight TO-DO app built with Django and React. It lets you create, update, and remove tasks while keeping the codebase clean, maintainable, and responsive.

## Features

- Add, edit, and delete TODOs
- Set due dates
- Mark TODOs as done

## Technologies:

- Django
- React (JavaScript)

## Future Improvements:

- Add user authentication
- Add user profiles with more customization options

## Setup

Clone the repository, then follow the backend (Django) and frontend (React) setup steps below.

### Django Backend

#### Install dependencies

```bash
pip install -r requirements.txt
```

#### Run database migrations

```bash
python manage.py migrate
```

#### Start the Django development server

```bash
python manage.py runserver
```

The Django backend should be running at `http://127.0.0.1:8000`.

### React Frontend

#### Install dependencies

From the frontend directory, install the packages listed in `package.json`:

```bash
npm install
```

#### Start the React development server

```bash
npm run dev
```

- The React frontend should be running at `http://localhost:5000`.

# Tests

## Backend

- Test 01: Create a todo task with all fields
- Test 02: Create a todo task with only required fields
