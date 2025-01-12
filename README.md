## [eza.web.id](https://eza.web.id)

![eza.web.id](https://raw.githubusercontent.com/rmdhnreza/eza.web.id/refs/heads/eza.web.id/assets/img/website.png)

- **Framework Hugo**: [eza.web.id](https://eza.web.id) dibuat menggunakan framework [Hugo](https://gohugo.io/).
- **Tema Stack**: Tema yang digunakan adalah [Stack](https://github.com/CaiJimmy/hugo-theme-stack) yang dibuat oleh [CaiJimmy](https://github.com/CaiJimmy)  
   Beberapa fitur tema [Stack](https://github.com/CaiJimmy/hugo-theme-stack) diantaranya:
  - Responsive images support
  - Lazy load images
  - Mode gelap / Dark mode
  - Local search
  - Integrasi PhotoSwipe
  - Template halaman arsip
  - Full native JavaScript
  - Tidak menggunakan Framework CSS manapun, membuatnya simple dan minimal
  - Daftar isi (Table of Content)
- **Hugo Modules**: Menggunakan [Hugo Modules](https://gohugo.io/hugo-modules/) untuk pengelolaan dependensi tema.

## Struktur Direktori

Karena website ini menggunakan [Hugo Modules](https://gohugo.io/hugo-modules/), beberapa file pada tema bawaan **Stack** telah ditimpa atau dimodifikasi. Berikut adalah file yang dimodifikasi:

```plaintext
.
assets
├── icons
│   ├── archives.svg
│   ├── calendar.svg
│   ├── categories.svg
│   ├── clock-edit.svg
│   ├── clock.svg
│   ├── code.svg
│   ├── facebook.svg
│   ├── home.svg
│   ├── pencil-exclamation.svg
│   ├── tags.svg
│   └── twitter.svg
├── img
│   └── avatar.svg
├── scss
│   ├── partials
│   │   └── highlight
│   │       ├── dark.scss
│   │       └── light.scss
│   ├── custom.scss
│   └── variables.scss
├── ts
│   └── main.ts
└── jsconfig.json
data
└── external.yaml # Vibrant.js ditimpa dengan `noop.js`
layouts
├── _default
│   ├── _markup
│   │   └── render-image.html
│   ├── archives.html
│   ├── baseof.html
│   ├── list.html
│   ├── single.html
│   └── sitemap.xml
├── partials
│   ├── article
│   │   ├── components
│   │   │   ├── categories.html
│   │   │   ├── content.html
│   │   │   ├── details.html
│   │   │   ├── header.html
│   │   │   ├── related-content.html
│   │   │   ├── social.html
│   │   │   └── tags.html
│   │   └── article.html
│   ├── article-list
│   │   ├── compact.html
│   │   └── tile.html
│   ├── comments
│   │   └── provider
│   │       └── disqus.html # `Click to View` comments
│   ├── data
│   │   └── title.html
│   ├── footer
│   │   ├── components
│   │   │   └── custom-font.html
│   │   └── custom.html
│   ├── head
│   │   └── custom.html
│   ├── helper
│   │   └── icon.html
│   ├── sidebar
│   │   └── left.html
│   ├── widget
│   │   ├── archives.html
│   │   ├── categories.html
│   │   ├── search.html
│   │   └── tag-cloud.html
│   └── pagination.html
├── shortcodes
│   ├── adsense.html
│   ├── center.html
│   ├── dlbox.html
│   ├── iframe.html
│   ├── img.html
│   ├── indent.html
│   ├── note.html
│   ├── spoiler.html
│   ├── tabs.html
│   ├── warn.html
│   ├── warning.html
│   └── youtube.html
├── index.html
└── robots.txt
hugo.json # Config menggunakan template `JSON`
```

## Lisensi

Repository ini menggunakan lisensi sesuai ketentuan pemilik tema [Stack](https://github.com/CaiJimmy/hugo-theme-stack) yaitu [GNU General Public License v3.0](https://github.com/rmdhnreza/eza.web.id/LICENSE/raw)
