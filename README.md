# AI Sound Designer

Fresh-start API-first chatbot project.

This version does **not** fake sound generation. The app is waiting for the real API details.

## Plan

1. Choose the sound API.
2. Collect the API documentation and key.
3. Understand the endpoint:
   - text-to-sound URL
   - request body
   - response format
   - whether generation is instant or job-based
4. Connect the API in `backend/main.py`.
5. Build the final chatbot interface around the real API response.
6. Deploy with API keys stored as environment variables.

## Current structure

```text
CHATBOT/
  backend/
    main.py
    requirements.txt
    .env.example
  frontend/
    index.html
    styles.css
    app.js
  API_CHECKLIST.md
  README.md
```

```

Then open:

```text
http://127.0.0.1:8000
```
