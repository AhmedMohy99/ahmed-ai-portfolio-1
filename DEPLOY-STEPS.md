# Step-by-Step: Deploy this portfolio to Vercel

## Method A — easiest method
1. Download the project ZIP.
2. Extract it on your computer.
3. Open the extracted folder.
4. Check that these files are inside:
   - index.html
   - style.css
   - script.js
   - vercel.json
5. Go to Vercel in your browser.
6. Sign in with GitHub.
7. Click **Add New Project**.
8. Choose **Browse** or upload the folder/repo depending on what Vercel shows.
9. If you are importing from GitHub:
   - create a new GitHub repo first
   - upload the files
   - push the repo
   - then import that repo into Vercel
10. Click **Deploy**.
11. Wait until Vercel gives you the live URL.
12. Open the URL and test every link.

## Method B — GitHub first, then Vercel
1. Go to GitHub.
2. Click **New repository**.
3. Name it something like: `ai-portfolio-ahmed-mohy`
4. Click **Create repository**.
5. Click **uploading an existing file**.
6. Drag these files into GitHub.
7. Commit the files.
8. Go to Vercel.
9. Click **Add New Project**.
10. Import the GitHub repo.
11. Framework preset:
    - choose **Other** or leave automatic
12. Build settings:
    - no build command needed
    - no output folder needed
13. Click **Deploy**.

## After deployment
1. Copy your Vercel URL.
2. Replace this line inside `index.html`:
   `https://your-vercel-domain.vercel.app`
   with your real Vercel website URL.
3. Re-upload or push the updated file.
4. Redeploy automatically.

## Important next step
Right now the project cards point to your main GitHub.
Later, replace each project card link with the real repo for:
- RAG System
- Object Detection
- MLOps Pipeline
- RL Agent
- Multimodal Assistant
