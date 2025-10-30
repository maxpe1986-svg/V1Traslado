<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/drive/1uhlvCc26OIiE5GplvIOsHcbntNx6_78M

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the required API keys in a local env file (do NOT commit this file).
    - To enable Google Maps Directions API (preferred): create a `.env` or `.env.local` with:
       `VITE_GOOGLE_MAPS_API_KEY=your-google-maps-api-key`
    - (Optional) If you want to keep using Gemini as a fallback, set:
       `API_KEY=your-gemini-api-key`
3. Run the app:
   `npm run dev`
