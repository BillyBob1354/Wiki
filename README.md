<h1 align="center">Krew Wiki</h1>

<h1 align="center">
    <img src="./docs/assets/img/logos/favicon.png" align="center" />
</h1>

<h3 align="center">A wiki for the online game Krew.io</h3>

<p align="center">
    <img src="https://img.shields.io/github/contributors/Krew-io/Wiki?style=for-the-badge&color=f26248">
    <img src="https://img.shields.io/github/last-commit/Krew-io/Wiki?style=for-the-badge&color=f26248">
</p>

---

## Requirements
 * [Node.js](https://nodejs.org)
 * [pnpm](https://pnpm.io)

## Contributing
Fork the repository and clone it.

This wiki utilizes docsify, which is an on-the-fly markdown renderer. To learn more about how to use it, visit their website [here](https://docsify.js.org/#/).

Wiki pages are written in markdown, which is essentially text files with additional formatting. You can also add HTML within the markdown files for more complex elements. If you are unfamiliar with markdown formatting, check out [this](https://www.markdownguide.org/cheat-sheet/) website to view the basics of markdown formatting. `index.html` and `sitemap.xml` can be ignored for your purposes.

To test your changes, navigate to the project directory and install dependencies:
```
pnpm i
```

Afterwards, start docsify:
```
pnpm dev
```

This will then host a webserver on `http://localhost:3000`, where you can view your changes.
