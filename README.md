# lixo.org

Personal landing page for Carlos Villela, hosted by GitHub Pages at
[https://lixo.org](https://lixo.org).

The site is intentionally plain HTML and CSS. It has no build step, package
manager, JavaScript, analytics, or runtime application dependencies.

## Local preview

Open `index.html` in a browser:

```sh
open index.html
```

## Deployment

GitHub Pages publishes the `master` branch. The custom domain is configured in
`CNAME`, so deployment is simply:

```sh
git push
```

## Assets

- `img/profile_big.jpg` is the profile and Open Graph image.
- `favicon.svg` is the cherry blossom favicon.
- `cv.vcf` is the downloadable contact card.
- `fonts/fontawesome` contains only the icon glyphs used by `index.html`.
- `fonts/handlee` contains a subset for the fixed page heading. It will need to
  be regenerated if the heading text changes.
