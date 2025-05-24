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
