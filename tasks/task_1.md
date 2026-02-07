# Learn Coding: Build Your First Website with Astro

## What you’re doing (big picture)

You will:

1. Set up Astro on your computer
2. Follow the official Astro tutorial step by step
3. Build a simple website for **homemade soap**
4. Put the website online so anyone can visit it

If you get stuck: **slow down and reread the last step**. That’s normal.

---

## Step 1: Install what you need (once)

You need two things:

### 1) Install Node.js

* Download **Node.js (LTS version)** from: [https://nodejs.org](https://nodejs.org)
* Install it using the default options

### 2) Install a code editor

* Download **Visual Studio Code (VS Code)**: [https://code.visualstudio.com](https://code.visualstudio.com)
* This is where you’ll write code

Done. You won’t need to touch this again.

---

## Step 2: Create your first Astro project

Open **Terminal** (Mac/Linux) or **Command Prompt** (Windows).

Run this command:

```
npm create astro@latest
```

When asked:

* Project name → pick anything (e.g. `my-first-astro-site`)
* Template → **Basic**
* TypeScript → **Yes**
* Install dependencies → **Yes**

Then run:

```
cd my-first-astro-site
npm run dev
```

Open the link shown in the terminal (usually `http://localhost:4321`).
You should see a website. 🎉

---

## Step 3: MOST IMPORTANT — do the official tutorial

Do **this tutorial fully, in order**:

👉 [https://docs.astro.build/en/tutorial/1-setup/](https://docs.astro.build/en/tutorial/1-setup/)

### Rules for the tutorial

* Follow **every step**
* Type the code yourself
* Don’t copy random solutions from Google
* If something breaks, compare your files with the tutorial

### What you should understand by the end

Don’t worry if it feels confusing at first. You’ll learn:

* How pages work
* How components work
* How files become URLs
* How Astro mixes HTML + JavaScript

You are **not allowed to skip this step**.

---

## Step 4: Your project — Homemade Soap website

After finishing the tutorial, build this small website.

### Pages you must have

Create these pages:

| Page    | URL        | Purpose                |
| ------- | ---------- | ---------------------- |
| Home    | `/`        | Intro + featured soaps |
| Soaps   | `/soaps`   | List of all soaps      |
| About   | `/about`   | Who makes the soap     |
| Contact | `/contact` | How to get in touch    |

Astro creates pages automatically based on files inside `src/pages`.

---

## Step 5: Store soap data (important concept)

Create a data file (for example: `src/data/soaps.js`).

Inside it, store an **array of objects** like this:

* soap name
* scent
* price
* ingredients
* whether it’s in stock

You will use this data to:

* show all soaps on the `/soaps` page
* show only some “featured” soaps on the homepage

This teaches you how real websites work with data.

---

## Step 6: Components (reusable pieces)

Create at least one component:

### Required component

* `SoapCard.astro`

  * Displays one soap
  * Receives data using **props**

Use the same component:

* on the homepage
* on the soaps page

This is a core skill.

---

## Step 7: Layout (shared structure)

Create one layout:

* Header (site name + navigation)
* Footer (simple text)

All pages should use the same layout so the site feels consistent.

---

## Step 8: Styling (keep it simple)

You can use:

* Basic CSS **or**
* Tailwind (optional)

No need to be fancy. Clean and readable wins.

---

## Step 9: Put the site online (deployment)

Choose **one** option and follow Astro’s guide:

* Netlify
  [https://docs.astro.build/en/guides/deploy/netlify/](https://docs.astro.build/en/guides/deploy/netlify/)
* Vercel
  [https://docs.astro.build/en/guides/deploy/vercel/](https://docs.astro.build/en/guides/deploy/vercel/)
* Cloudflare Pages
  [https://docs.astro.build/en/guides/deploy/cloudflare/](https://docs.astro.build/en/guides/deploy/cloudflare/)

End result:

* A public URL anyone can visit

---

## Final checklist (definition of “done”)

You are finished when all are true:

* [ ] Astro tutorial completed
* [ ] Website runs locally
* [ ] 4 pages exist and are linked together
* [ ] Soap data stored in an array
* [ ] Same component reused in multiple places
* [ ] Shared layout across pages
* [ ] Website deployed online

---

## Important mindset notes

* Confusion is normal
* Breaking things is normal
* Googling errors is normal
* Progress > perfection

Finish this and you’ll **actually be coding**, not just “learning about coding”.
