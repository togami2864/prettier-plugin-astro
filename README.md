# Beta Prettier Plugin for [Astro](https://github.com/snowpackjs/astro) -- 🚧 Caution! May break your project 🚧

## Install [prettier-plugin-astro](https://www.npmjs.com/package/prettier-plugin-astro)

1. `yarn add --dev prettier-plugin-astro` or `npm i -D prettier-plugin-astro`
1. `yarn prettier .` to check your formatting / `yarn prettier -w .` to fix your formatting.
1. Add

```json
"format": "yarn prettier -w .",
```

to your `package.json` and create a `.prettierignore` to ignore any files.

## Contributing

To get setup:

1. `git clone git@github.com:snowpackjs/prettier-plugin-astro.git`
1. `yarn`
1. Run tests with `yarn test`
1. Lint code with `yarn lint`
1. Format code with `yarn format`
1. Run `yarn changeset` to add your changes to the changelog on version bump.
   Most changes to the plugin should be `patch` changes while we're before `1.0.0`.

## Resources for contributing

- [prettier rationale](https://prettier.io/docs/en/rationale.html)
- [prettier plugin docs](https://prettier.io/docs/en/plugins.html)
- [svelte prettier plugin](https://github.com/sveltejs/prettier-plugin-svelte)
- [prettier html formatter](https://github.com/prettier/prettier/tree/main/src/language-html)
