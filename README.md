# Weather Dashboard

![Status](https://img.shields.io/badge/status-coursework-blue)

Coursework weather dashboard for searching cities, viewing forecast data, and keeping search history.

**Built with:** TypeScript, Vite, Express, OpenWeather, Day.js.

## Run locally

Requires Node.js/npm and an OpenWeather API key. From the repository root:

```bash
npm install
```

Create a private `server/.env`:

```dotenv
API_BASE_URL=https://api.openweathermap.org
API_KEY=replace_with_your_openweather_key
PORT=3001
```

The code reads `API_KEY`, not the older README's `weathermapAPI_KEY`.

```bash
npm run start:dev
```

Open the frontend address printed in the terminal.

## Checks

`npm run build` builds the frontend only; `npm run build --prefix server` builds the backend. `npm test` is a placeholder. Check city searches, forecasts, and history manually.

Setup instructions were checked against source; builds and application behavior have not been rerun during this cleanup.
