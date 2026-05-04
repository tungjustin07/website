# website

Personal website at [tungjustin.com](https://tungjustin.com). Static HTML, deployed on Cloudflare Workers.

## Layout

```
public/
  index.html       # home (merged with About content, in the style of patrickcollison.com)
  offerings.html   # services / what I do
  readings.html    # reading list
  advice.html      # notes
  styles.css
  photo.jpg
wrangler.toml      # Cloudflare Workers config
package.json
```

## Develop

```bash
npm install
npx wrangler dev          # local preview
```

## Deploy

```bash
npx wrangler deploy
```

Cloudflare Workers serves files out of `public/`. The home-page layout is inspired by [davidronen.com](https://davidronen.com); typography/structure follows [patrickcollison.com](https://patrickcollison.com).

## Contact

`justin@tungjustin.com`
