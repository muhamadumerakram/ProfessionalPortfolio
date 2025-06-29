# GitHub Upload Guide - Muhammad Umer Portfolio

## Step 1: Create GitHub Repository
1. Go to github.com and sign in
2. Click "New repository" (green button)
3. Repository name: `muhammad-umer-portfolio`
4. Description: "Professional QA Engineer Portfolio Website"
5. Make it Public
6. Don't initialize with README
7. Click "Create repository"

## Step 2: Create These Files in Your GitHub Repository

### ROOT DIRECTORY FILES:
1. package.json (copy from Replit)
2. README.md (copy from Replit)
3. .gitignore (copy from Replit)
4. tsconfig.json
5. vite.config.ts
6. tailwind.config.ts
7. postcss.config.js
8. components.json
9. drizzle.config.ts

### CREATE FOLDER STRUCTURE:
```
muhammad-umer-portfolio/
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   └── lib/
│   └── public/
├── server/
└── shared/
```

### FILES TO COPY FROM REPLIT:
- All files in client/src/components/
- All files in client/src/pages/
- All files in server/
- All files in shared/

## Step 3: Upload Assets
Upload these files to client/public/:
- resume.pdf (your resume)
- certificate.pdf (Microsoft Learn certificate)
- profile.jpg (your profile picture)

## Step 4: After Upload
1. Go to repository Settings
2. Enable GitHub Pages (if you want free hosting)
3. Or deploy to Vercel/Netlify for better performance

## Important Notes:
- Don't upload node_modules folder
- Make sure .gitignore is uploaded first
- Upload package.json early so others can see dependencies