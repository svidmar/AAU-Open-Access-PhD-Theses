# AAU Open Access PhD Theses

Website showing Open Access PhD theses from Aalborg University.

- Export report from Pure using `AAUOPENTHESES_Version3.json` report definition
- Frontend: plain HTML, CSS, JS (no backend)
- Series names normalized via `seriesMapping`:
   const seriesMapping = {
    "": "Other",
    "Ph.d.-serien for Det Humanistiske Fakultet, Aalborg Universitet": "SSH",
    "Ph.d.-serien for Det Humanistiske og Samfundsvidenskabelige fakultet, Aalborg Universitet": "SSH",
    "Ph.d.-serien for Det Ingeniør- og Naturvidenskabelige Fakultet, Aalborg Universitet": "ENG",
    "Ph.d.-serien for Det Samfundsvidenskabelige Fakultet, Aalborg Universitet": "SSH",
    "Ph.d.-serien for Det Sundhedsvidenskabelige Fakultet, Aalborg Universitet": "HEALTH",
    "Ph.d.-serien for Det Teknisk-Naturvidenskabelige Fakultet, Aalborg Universitet": "ENG",
    "Ph.d.-serien for Det Tekniske Fakultet for IT og Design, Aalborg Universitet": "TECH",
    "PhD Series, Faculty of Engineering and Science, Aalborg University": "ENG",
    "PhD Series, Technical Faculty of IT and Design, Aalborg University": "TECH",
    "PhD Series, The Doctoral School of Social Sciences and Humanities, Aalborg University": "SSH",
    "Aalborg Universitet. Det Humanistiske Fakultet. Ph.D.-Serien": "SSH",
    "Aalborg Universitet. Det Samfundsvidenskabelige Fakultet. Ph.D.-Serien": "SSH",
    "Aalborg Universitet. Det Sundhedsvidenskabelige Fakultet. Ph.D.-Serien": "HEALTH"
};

To update:
1. Run report in Pure → export Excel → overwrite existing xlsx file
2. Reload site
