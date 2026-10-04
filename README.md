# Hanka

Web značky Hanka — staroružová homepage s vintage kvetmi a monogramom HV.

## Vercel

Projekt je pripravený ako statický web (bez build kroku).

1. Importujte GitHub repo `matus-babiak/hanka` do Vercelu
2. Framework Preset: **Other**
3. Build Command: nechajte prázdne
4. Output Directory: `.` (root) — alebo nechajte default, keď nie je `public/`
5. Production branch: `main`

Konfigurácia je v `vercel.json` (`framework: null`, `cleanUrls`).

## Lokálne

```bash
python3 -m http.server 8080
```

Potom: [http://localhost:8080](http://localhost:8080)
