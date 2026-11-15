# Luit Motors – Second-hand car dealership (Assam)

A fast, single-page website for a used car dealership in Assam. Visitors pick **Low budget** (up to ₹5 lakh) or **High budget** (above ₹5 lakh), filter by city, search, sort, and enquire on WhatsApp.

No build step, no dependencies. Plain HTML, CSS and JavaScript.

## Run locally
Open `index.html` in a browser.

## Customise
Open `index.html` and edit the `CONFIG` and `CARS` blocks near the bottom:
- `whatsapp`, `phoneDisplay`, `address`: your real contact details
- `budgetLimit`: price that separates low and high budget
- `CARS`: your stock (the entries are sample data)

## Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit: Luit Motors website"
git branch -M main
git remote add origin https://github.com/<your-username>/luit-motors.git
git push -u origin main
```

## Host free on GitHub Pages
Repo → Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / root → Save.
Your site will be live at `https://<your-username>.github.io/luit-motors/`.
