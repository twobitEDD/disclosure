# CO2 Trust recall notice

Static public site for the biochar recall. It does not use a marketplace, accounts, payments, or an API.

- `/` — site-wide pause notice
- `/recall-letter/` — customer letter (counsel’s wording, grammar only)
- `/faq/` — 70 ppm is the biochar result, not the soil. Recommended mix is 5% to 10%. Heavier use: email recall@co2trust.earth
- Any other path returns visitors to the notice

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 4173
```

Then visit http://127.0.0.1:4173/
