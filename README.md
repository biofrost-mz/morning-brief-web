# Morning Brief – veřejný web

Statický web **https://morning-brief.zichmichal.cz/** – veřejná edice „jen zprávy“ ranního briefu.

> ⚠️ **Tento repozitář je generovaný.** Obsah (`*.html`, `sitemap.xml`, assety) každé ráno přepisuje workflow
> v soukromém repu [`morning-brief`](https://github.com/biofrost-mz/morning-brief) skriptem
> `build_public_site.py`. Ruční úpravy HTML zde budou při dalším běhu přepsány – měň generátor.

| Soubor | Obsah |
|---|---|
| `index.html` | nejnovější brief + archiv |
| `brief-YYYY-MM-DD.html` | jednotlivé dny |
| `o-projektu.html`, `zdroje.html`, `kontakt.html`, `ochrana-osobnich-udaju.html` | informační stránky |
| `potvrzeno.html`, `odhlaseno.html`, `odkaz-vyprsel.html` | cílové stránky odběru (Google Apps Script) |
| `sitemap.xml`, `robots.txt`, `og.png`, `logo.png`, `favicon.png`, `.nojekyll` | SEO a assety |

Web neobsahuje žádná osobní data (kalendář, úkoly, svoz odpadu) – ta zůstávají v soukromém repu.
Formulář odběru posílá e-mail na Google Apps Script; seznam odběratelů je jen v Google Sheetu.
