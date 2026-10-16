KINSHIP — FAMILY HEALTH HISTORY MAPPER

Run locally
1. Download or copy this folder to your computer.
2. Double-click index.html to open it in a modern browser.
3. The Overview page shows a quick dashboard. Use the top navigation to open Family log and add fictional entries, then Visit summary to review the descriptive summary and questions.
4. Click “Print / save summary” on Visit summary to print or save it as a PDF.

CARE GUIDE
The Visit summary includes a rule-based Care Guide that repeats each logged item and suggests questions to discuss with a healthcare professional. It is not a live AI agent and does not decide seriousness, recommend a specific doctor, diagnose, estimate risk, or recommend treatment.

Publish on Vercel with the CLI
1. Install Node.js if it is not already installed: https://nodejs.org/
2. Open a terminal in this folder.
3. Run: npx vercel
4. Follow the prompts to sign in and deploy. For a public production URL, run: npx vercel --prod
5. Open the URL Vercel prints and check the demo. Paste that URL into the hackathon form.

This is a static website; it has no backend and needs no build step. In Vercel project settings, use the current folder as the root, leave the framework preset as “Other”, leave the build command blank, and use “.” as the output directory if asked.

DEMO SAFETY
The app stores entries only in JavaScript memory in the open browser tab. It does not send entries to a server or retain them after the tab closes. Use fictional data for the hackathon demonstration. The summary reports entered counts and family sides only; it is not a diagnosis, genetic-risk estimate, or medical recommendation.
