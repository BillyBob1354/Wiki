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

## Contribute
Make sure you have [pnpm](https://pnpm.io) installed before continuing.

Fork the repository and clone it.

The wiki uses something called docsify, which is an on-the-fly markdown renderer. To learn more about docsify and how to use it, visit their website [here](https://docsify.js.org/#/).

All of the wiki is made in markdown, which is essentially text files with additional formatting. You can also add HTML within the markdown files for more complex elements. If you are unfamiliar with markdown formatting, check out [this](https://www.markdownguide.org/cheat-sheet/) website to view the basics of markdown formatting. `index.html` and `sitemap.xml` can be ignored.

To test your changes, navigate to the parent directory of the `docs` folder and install project dependencies:
```
pnpm i
```

Afterwards start docsify:
```
pnpm dev
```

It will then host a webserver on `http://localhost:3000`, where you can view your changes.
