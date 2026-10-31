# M44Brigade website

The Astro site rebuilds the Dutch Memoir ’44 Brigade website from the recovered
HTML in `20260610223132/`. Recovered pages are presented in a responsive,
charcoal-and-brown layout inspired by the original site.

## Development

```sh
npm install
npm run dev
npm run build
npm run preview
```

Recovered content is stored as individual Markdown files in `src/pages/`, with
filenames matching each page’s URL slug (`index.md` is the home page). Each
file has a title in its frontmatter and contains the recovered page content.
The pages share an Astro layout, and the five photos included in the download
are available on the Foto’s page.

## Known gaps in the recovered copy

- The Dutch Open 2024 event page and several individual news posts were not
  captured. The Tournament US Open page is represented only by its calendar
  listing; its full event details were not captured.
- The contact page had a form, but no working form service or contact address
  was included.
- Most images and downloadable documents are referenced by the archived HTML
  but were not included as files; links are retained where the web archive has
  a captured copy.
