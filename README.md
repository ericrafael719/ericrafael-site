# Eric Rafael — Spoken Word

Static site for Eric Rafael, spoken word artist.

## Pages
- `index.html` — Home / hero
- `bio.html` — About + portrait
- `projects.html` — All projects, featuring **Bouquet of Words**
- `now.html` — What he's currently working on
- `book.html` — Booking inquiry form + contact info

## Drop Your Images Here

Two image slots already wired up. Save your files at these exact paths:

| File path | What it is |
|---|---|
| `assets/eric-rafael.jpg` | The portrait of Eric (suit, boardroom). Used on bio.html. |
| `assets/bouquet-of-words.jpg` | The "Bouquet of Words" collage artwork. Used on index.html + projects.html. |

Aspect ratios used:
- Portrait: 4:5 (object-fit: cover, so any portrait orientation works)
- Bouquet: square works best

## Run Locally

```bash
cd "Eric Rafael"
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

Drag-and-drop the folder to Netlify, or push to GitHub and connect to Netlify/Vercel. No build step required.

## Update Booking Email

Change `hello@ericrafael.com` in `book.html` (3 places) to Eric's real address before going live. Same for the social links (`href="#"`) in every page footer.
