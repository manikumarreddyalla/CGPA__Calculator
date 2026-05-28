<<<<<<< HEAD
Vel Tech Smart CGPA Calculator — Tiny edition
===========================================

This workspace now contains a single ultra-lightweight, framework-free CGPA demo you can open in any browser.

Where to run
- Open the demo directly:

   ```powershell
   start "" "c:\Users\allas\OneDrive\Desktop\CGPA Calculator\lite\index.html"
   ```

- Or serve the `lite` folder (recommended for export/download features):

   ```powershell
   cd "c:\Users\allas\OneDrive\Desktop\CGPA Calculator\lite"
   # with Python 3
   python -m http.server 5173
   # then open http://localhost:5173
   ```

What it does
- Search subjects (by code, name, alias) and add them to a semester.
- Auto-loads credits from the embedded subject list.
- Select grades, compute SGPA for the current semester.
- Save semesters to `localStorage`, compute CGPA across saved semesters.
- Export saved data to JSON and clear saved semesters.
- Includes static Guide, FAQ, About, Contact, Privacy Policy, Terms, and robots.txt pages for a publishable site structure.

Notes
- The full subject catalog is embedded inside `lite/index.html` for a self-contained experience.
- The original React/Tailwind frontend and backend scaffolding have been removed to keep the workspace minimal.
- Replace the contact email placeholder in `lite/contact.html` before publishing.
- If AdSense asks for ads.txt, create it only after you know your real publisher ID from AdSense.
- See `ADSENSE_CHECKLIST.md` before adding ad code or applying for AdSense.

If you want anything changed (smaller file, different grade scale, or a downloadable zip), tell me what to do next.
=======
# CGPA__Calculator
>>>>>>> 8184143590edf78a901aaf332d27024051d3f3ec
