# Bitrise Blog

Using NextJS and React

## Development

- `cp .env.example .env`
- Update the `.env` file
- `npm install`
- `npm start` (or `PORT=1234 npm start`)
- Navigate to [localhost:3000](http://localhost:3000)

## Sitemap

You can generate a sitemap running `npm run sitemap`.

If you'd like to use a custom path, use `npm run sitemap -- /your/custom/path/sitemap.xml`.

## Algolia

The site uses Algolia instant search, to reindex the posts run `npm run algolia`

*Note:* Make sure you have the proper `ALGOLIA_*` environment variables set.
