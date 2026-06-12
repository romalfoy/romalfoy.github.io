# romalfoy.github.io

Personal academic website for **Romal Ramadhan** — PhD Candidate at UT Austin (Bureau of Economic Geology) & Researcher at Los Alamos National Laboratory.

Live at: **https://romalfoy.github.io**

## Stack

Pure HTML/CSS — no frameworks, no build step. Works straight out of a GitHub Pages repository.

## How to deploy

1. Create a new **public** GitHub repository named exactly `romalfoy.github.io`
2. Upload `index.html` (and this README) to the root of the repo
3. Go to **Settings → Pages** and confirm source is set to **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://romalfoy.github.io` within 1–2 minutes

## Customisation checklist

- [ ] Update Google Scholar URL in the contact section with your real profile link
- [ ] Update ResearchGate URL if different
- [ ] Add a real profile photo (add `photo.jpg` to the repo and update the hero section)
- [ ] Add your LANL email or profile link when public
- [ ] Update the "Countries of research" stat card if desired
- [ ] Swap the `mailto:` links if you prefer a different contact email

## Updating publications

Each publication lives in a `.pub-item` div in `index.html`. Copy an existing block and adjust the year, title, authors, and journal fields.
