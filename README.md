# România — Identitate Vizuală Națională (deploy secundar)

> **Acest repo este o copie a [`moldluca/romania-visual-identity`](https://github.com/moldluca/romania-visual-identity).**
> Conținutul e identic — 144 din 145 de fișiere sunt bit-cu-bit aceleași. Singura diferență
> este fișierul `CNAME`, care publică același site pe un al doilea domeniu.
>
> **Modificările se fac în `romania-visual-identity`**, care e sursa de adevăr. Repo-ul de față
> există doar ca să servească domeniul secundar.

**Live:** https://telefon.romania.perpetuummobile.tech/
**Sursa principală:** https://romania.perpetuummobile.tech/

## Ce conține

Website-ul de prezentare al propunerii de brand de țară pentru România, împreună cu brand
book-ul complet (capitolele 1–17 în `brandbook/`) și kit-ul descărcabil `brand-kit.zip`.
Site-ul e bilingv RO / EN, traducerile fiind în `lang.js`.

Secțiunea de mockup-uri pentru aplicație și ecrane digitale se află în
`brandbook/cap-14-17.html` — *„Ecrane digitale în spații publice"*.

Pentru descrierea detaliată a structurii, vezi README-ul din repo-ul principal.

## Rulare locală

```bash
python3 -m http.server 8000
# apoi deschide http://localhost:8000
```

## Deploy

GitHub Pages din branch-ul `main`, domeniu custom prin `CNAME`.
