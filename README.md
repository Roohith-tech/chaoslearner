# Chaos Learning

Sovereign Open Framework Platform © 2026
Platform Architect: V B Roohith Saravanan, roohithsara19@gmail.com

Static site: CBSE, ICSE and IB, Classes 6 to 8, Science and Maths, 8 chapters each.
No build step and no dependencies. Everything lives in `index.html`; `vercel.json` adds security headers.

## Deploy to Vercel

**Option A: CLI (about a minute)**
```
cd this-folder
npx vercel          # first run: log in and accept the defaults (framework: Other, no build command)
npx vercel --prod   # publish to your production URL
```

**Option B: GitHub**
1. Push this folder to a new GitHub repo.
2. In Vercel choose Add New, then Project, and import the repo.
3. Framework preset: Other. Leave Build Command and Output Directory empty. Click Deploy.

## Editing content
Chapter data sits near the top of the script in `index.html` (`CL_PARTS` blocks and the `CL` object).
Commit the change and Vercel redeploys automatically (Option B), or run `npx vercel --prod` again (Option A).
