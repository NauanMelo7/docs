# Mintlify Starter Kit

Use the starter kit to get your docs deployed and ready to customize.

Click the green **Use this template** button at the top of this repo to copy the Mintlify starter kit. The starter kit contains examples with

- Guide pages
- Navigation
- Customizations
- API reference pages
- Use of popular components

**[Follow the full quickstart guide](https://starter.mintlify.com/quickstart)**

## Development

Instala a [Mintlify CLI](https://www.npmjs.com/package/mintlify) para ver a documentação em local. Na pasta `docs` (onde está o `docs.json`):

```bash
npm i -g mintlify
mintlify dev
```

Abre o preview em `http://localhost:3000`.

> **Nota:** Em versões antigas da CLI o pacote era `mint` e o comando `mint dev`. Se já tiveres `mint` instalado, podes usar `mint dev` na pasta `docs`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
