# AI Art Evaluator Platform

This repository contains a simple Flask backend for evaluating uploaded images.

## Running the Backend

1. Install the Python dependencies:

```bash
pip install -r requirements.txt
```

2. Start the server:

```bash
python backend/app.py
```

The `/api/evaluate` endpoint accepts an image file uploaded via `multipart/form-data` under the field name `image`.

## Running the Frontend

1. Install Node dependencies:

```bash
cd frontend
npm install
```

2. Start the React development server:

```bash
npm start
```

The React app is configured with a `proxy` to `http://localhost:5000`, allowing API requests to `/api/*` without CORS issues.
