# MATH101 Study Tracker

A simple, responsive study planner for the FY BCA Semester I Mathematical and Statistical Techniques (MATH101) backlog.

## Features
- 30-day plan based on the syllabus you supplied
- Pending / in-progress / completed status for each day
- Dashboard progress, study time, practice score and streak
- Daily notes, mistakes and study minutes
- Separate study journal
- Formula sheet
- Export and import JSON backups
- Mobile-friendly layout

## Run locally
This is a static website. Open `index.html` in a browser. For the best local development experience, use VS Code with the Live Server extension.

## Deploy to Vercel
1. Extract this ZIP on your computer.
2. Create a new GitHub repository, for example `math101-study-tracker`.
3. Upload `index.html`, `style.css`, `app.js`, `vercel.json`, and `README.md` to the repository root.
4. Sign in to Vercel with GitHub and choose **Add New → Project**.
5. Import `math101-study-tracker`.
6. Framework preset: **Other**. Leave Build Command and Output Directory blank unless Vercel asks otherwise.
7. Click **Deploy**. Vercel will give you a live URL.

## Important data note
This first version saves data in the current browser's local storage. It does not sync automatically between browsers or devices. Use **Export backup** to save a JSON backup, and **Import backup** to restore it. Clearing browser site data can erase local records. A cloud database and login can be added in a later version.

## Study plan note
The 30-day roadmap is a suggested revision schedule, not an official exam timetable. Follow the methods and conventions taught by your college for quartiles, variance and other numerical methods.
