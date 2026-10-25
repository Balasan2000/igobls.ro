# IGO BLS - Website

Site simplu, static, pentru IGO BLS (Large Format Printing, Branding & Design).

## Cum să editezi site-ul

1. **Texte**  
   Deschide `index.html` și modifică textele direct în cod (sunt clar structurate pe secțiuni).

2. **Poze**  
   - Pune pozele noi în folderul `images/`  
   - În `index.html`, în secțiunea Galerie, adaugă linii de tipul:  
     ```html
     <img src="images/nume-poza.jpg" alt="Descriere">
     ```

3. **Culori**  
   Deschide `style.css` și modifică valorile din `:root` (la începutul fișierului):
   ```css
   --blue: #0077cc;   /* culoarea principală */
   ```

4. **Logo**  
   Înlocuiește fișierul `images/logo.jpg` cu noul logo (preferabil pătrat).

## Publicare pe GitHub Pages

1. Creează un repository nou pe GitHub
2. Încarcă toate fișierele (`index.html`, `style.css` și folderul `images`)
3. Mergi la Settings → Pages
4. Source: Deploy from a branch → main / root
5. Site-ul va fi disponibil la: `https://numele-tau.github.io/numele-repo/`

## Structură fișiere

```
├── index.html          ← pagina principală
├── style.css           ← designul
└── images/
    ├── logo.jpg
    ├── fata-pliant.png
    └── (adaugă aici pozele tale)
```

---

**Notă:** Fișierul `spate-pliant.png` nu a putut fi copiat automat. Dacă îl ai, pune-l în folderul `images/` și va apărea în Galerie.
