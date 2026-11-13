# HanakTech — web

Statický web značky HanakTech: audit IT a AI procesů, zaškolení, správa a rozvoj, firemní řešení na míru.

## Nasazení

Web se nasazuje automaticky na GitHub Pages. Každý push do větve `main` spustí workflow `.github/workflows/pages.yml`, který nasadí obsah repozitáře tak, jak je.

## Lokální náhled

```bash
python3 -m http.server 4173
```

Pak otevřít <http://localhost:4173>.
