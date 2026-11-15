# Cambodia Digital E-Commerce Final Demo

The main presentation is **14 slides total, including the final Thank you / Q&A slide**. It keeps the original purple/cyan style, embedded fonts, English/Khmer, theme controls, screenshot zoom and presenter notes.

## Preview locally

Run in this folder:

```sh
python3 -m http.server 4174 --bind 127.0.0.1
```

Open http://127.0.0.1:4174/?lang=en or http://127.0.0.1:4174/?lang=km.

## Present

- Arrow keys / Space / PageDown: next slide or architecture step.
- ArrowLeft / PageUp: previous slide or step. Home / End: first / closing slide.
- F: fullscreen. T: light/dark. L: English/Khmer. P: print.
- N or Notes: presenter cues, hidden by default and excluded from print.
- Screenshot choices switch the visible UI. Click the image to zoom; Escape closes it.
- Slide 14 closes with Thank you / Q&A and links to the live demo, customer journey, admin screenshots and cover.

## Separate technical reference

`technical-reference.html` preserves the complete 19-slide version, including the former live-demo checklist and detailed Keycloak/setup appendices. It uses the same `assets/` folder. This reference is optional and is not part of the 14-slide main presentation.

Current production Compose: Vercel frontend, backend host proxy, Django, persistent PostgreSQL, Keycloak, Redis and Celery. Historical console captures may display an earlier demo hostname. Six existing stock helper tests passed on 15 November 2026; this does not establish full end-to-end or bank-settlement acceptance. Demo QR codes are not proof of bank payment.

Only local files were updated. No deployment was performed.

## PowerPoint versions

Both versions contain 14 slides with editable text, tables and diagrams, plus bilingual presenter notes.

- [Dark mode](powerpoint/Cambodia%20Digital%20E-Commerce%20-%20Final%20Presentation.pptx)
- [Light mode](powerpoint/Cambodia%20Digital%20E-Commerce%20-%20Final%20Presentation%20-%20Light%20Mode.pptx)

Use the HTML presentation for interactive screenshot galleries, language switching and fullscreen image zoom.
