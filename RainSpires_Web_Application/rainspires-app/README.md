# RainSpires demo web application

A responsive React + Vite prototype for the RainSpires smart water-management platform.

## Run locally
1. Install Node.js 20 or later.
2. In this folder run `npm install`
3. Run `npm run dev`
4. Open the local URL printed by Vite.

## Build
Run `npm run build`. The production output is in `dist/`.

## Deploy to Vercel or Netlify
- Push this folder to a GitHub repository.
- Import the repository into Vercel or Netlify.
- Build command: `npm run build`
- Output directory: `dist`
- No environment variables are required for this demo.

## Important demo limitations
- Sensor values and weather are illustrative, not live hardware/API readings.
- The area map is a stylized sample visual, not verified Chennai density data.
- Checkout is a demonstration only; no payment is collected.
- Authentication, Supabase persistence, actual map tiles, live weather, Arduino gateway, email/SMS, and production order management still need backend/API configuration.
- pH and turbidity alone cannot establish drinking-water safety.
