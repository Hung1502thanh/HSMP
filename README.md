# H SMP

Node.js 24 server for the H SMP landing page.

## Requirements

- Node.js 24.x

## Run locally

```bash
npm start
```

Open <http://localhost:3000> in a browser. Set `PORT` to use another port:

```bash
PORT=8080 npm start
```

For development, use Node.js watch mode:

```bash
npm run dev
```

The server also exposes `GET /healthz` for deployment health checks.
