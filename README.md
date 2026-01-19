Me-API Frontend

Quick start:

```bash
cd client
npm install
npm run dev
```

The app expects `VITE_API_BASE_URL` in `.env.local` (defaults to http://localhost:5000/api).

To use a local mock backend instead of your real API (useful while server is down), set in `.env.local`:

```
VITE_API_MOCK=true
```

With the mock enabled the UI will respond without the backend and PATCH requests will update in-memory data.
