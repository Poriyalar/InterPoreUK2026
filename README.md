# InterPore UK Chapter 2026 — Conference Website

9th Annual Conference on Porous Media · 1–2 September 2026 · Heriot-Watt University, Edinburgh

---

## Hosting on GitHub Pages

### First-time setup

1. Create a new GitHub repository (e.g. `interpore-uk-2026`)
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch, `/ (root)` folder → click **Save**
6. Your site will be live at `https://<your-username>.github.io/interpore-uk-2026/` within a minute or two

### Custom domain (optional)
If you want a URL like `interpore2026.hw.ac.uk`:
- Add a `CNAME` file to the repo root containing your domain
- Configure DNS with your IT team

---

## Giving Sarah Edit Access

1. Go to the repo → **Settings → Collaborators**
2. Click **Add people** → search for Sarah's GitHub username
3. Set role to **Write** — she can then edit `index.html` directly in the browser (no git knowledge required: click the file → pencil icon → edit → commit)

---

## Things to update before going live

Search the file for `TODO` comments — there are 5:

| Location | What to add |
|---|---|
| Hero "Submit Abstract" button | Real abstract submission URL |
| About section CTA | Same abstract submission URL |
| Registration "Register Now" button | Real registration URL |
| Venue travel info | More specific transport details |
| Footer contact link | Real contact email address |

Also consider:
- Replacing the map placeholder with an embedded Google Maps iframe
- Adding a programme/schedule section once confirmed
- Updating date status badges — the script auto-detects past/upcoming/closing soon

---

## File structure

```
interpore-uk-2026/
└── index.html       # Everything is in one file — no build tools needed
```

Single-file design means Sarah can edit it entirely in the GitHub web editor.
