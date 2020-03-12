# @pkmn/eslint-config
[![npm version](https://img.shields.io/npm/v/@pkmn/eslint-config.svg)](https://www.npmjs.com/package/@pkmn/eslint-config)&nbsp;

ESLint configuration based on Pokémon Showdown's style used by `@pkmn` projects:

```json
{
  "extends": "@pkmn"
}
```

**NOTE:** Ideally this package would extend an `@pokemon-showdown/eslint-config`
and just override the places where it differs (eg. spaces vs. tabs, combine types
and no-types into one file). Until then, this package copies Pokémon Showdown's
configs and edits are made in line.

This package is distributed under the terms of the [MIT License][0].

  [0]: https://github.com/pkmn/eslint-config/blob/master/LICENSE
