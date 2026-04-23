# InterPore UK Chapter 2026 — Conference Website

9th Annual Conference on Porous Media · 1–2 September 2026 · Heriot-Watt University, Edinburgh

link --- https://poriyalar.github.io/InterPoreUK2026/

---

## Hosting on GitHub Pages

### Custom domain (optional)
If you want a URL like `interpore2026.hw.ac.uk`:
- Add a `CNAME` file to the repo root containing your domain
- Configure DNS with your IT team

--

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
