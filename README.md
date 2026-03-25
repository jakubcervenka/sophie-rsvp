# Sophie RSVP landing page

Minimal GitHub Pages landing page with embedded Google Form.

## Google Form spec

Title:
- Přijdeš na oslavu prvních narozenin Sophie v Lajce?

Questions:
1. Jméno a příjmení
2. Přijdeš?
   - Ano
   - Ano, přijdu +1
   - Ano, přijdu +2 a více
   - Bohužel nepřijdu
3. Kolik vás celkem přijde?
4. Přijdete i s dětmi?
   - Ano
   - Ne
5. Poznámka

## Embed steps

1. Create the Google Form under the `cervenkakuba` account.
2. In Google Forms, open `Send` -> `<>` Embed HTML.
3. Copy the iframe src URL.
4. Replace `REPLACE_WITH_GOOGLE_FORM_ID` in `index.html` with the real form embed URL.

## Publish on GitHub Pages

1. Create a new GitHub repo, e.g. `sophie-rsvp`.
2. Upload `index.html` and `styles.css`.
3. In GitHub repo settings -> Pages:
   - Source: Deploy from a branch
   - Branch: main / root
4. Your page will be published at:
   `https://<your-github-username>.github.io/sophie-rsvp/`

## QR target

Use the final GitHub Pages URL as the QR destination.
