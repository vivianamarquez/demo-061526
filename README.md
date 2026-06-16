# Simple Vercel Demo

This repo contains the simplest possible Vercel-ready website: one static
`index.html` file at the project root.

## What you need for Vercel

1. A GitHub account.
2. A Vercel account.
3. This project pushed to a GitHub repository.

## Deploy with GitHub and Vercel

1. Commit the files:

   ```bash
   git add index.html README.md
   git commit -m "Add simple Vercel demo"
   ```

2. Push to GitHub:

   ```bash
   git push
   ```

3. Open Vercel and click **New Project**.
4. Import the GitHub repository.
5. Keep the default settings:
   - Framework Preset: Other
   - Build Command: leave empty
   - Output Directory: leave default
6. Click **Deploy**.

That is it. There is no `package.json`, install command, build command, or
environment variable needed for this static HTML demo.
