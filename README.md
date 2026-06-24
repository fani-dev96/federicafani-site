# federicafani.com

Sito personale di Federica Fanì — Social Media Manager, Sviluppatrice, Fotografa.

## Stack
- [Astro](https://astro.build/) — framework
- CSS vanilla con variabili custom — niente framework CSS
- Deploy su [Vercel](https://vercel.com/)
- Dominio su [Namecheap](https://namecheap.com/)

## Struttura
```
src/
  components/    # Navbar, Footer, componenti riutilizzabili
  layouts/       # Layout base
  pages/         # Pagine del sito
  styles/        # CSS globale
public/
  images/        # Foto profilo, OG image
  foto/          # Galleria fotografica
```

## Sviluppo locale
```bash
npm install
npm run dev
```

## Deploy
Push su `main` → Vercel fa il deploy automaticamente.
