# [jrvs.io](https://jrvs.io/) 🔗

[![Netlify Status](https://api.netlify.com/api/v1/badges/6c1d7761-137b-40e8-b93a-1f6b06430e38/deploy-status)](https://app.netlify.com/sites/jrvs/deploys)

Personal link shortener powered by [@kentcdodds](https://kentcdodds.com/)'s clever [netlify-shortener](https://github.com/kentcdodds/netlify-shortener).

## Usage

### View existing shortcodes:

[See `_redirects`.](_redirects)

### Create new shortcode:

```bash
npm run shorten https://github.com/jakejarvis gh
```

or:

```bash
npm link   # run once to set up
shorten https://github.com/jakejarvis gh
```

## License

This project is distributed under the [MIT license](LICENSE.md).
