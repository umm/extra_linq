# ExtraLINQ

*
* Forked from [mariusschulz/ExtraLINQ](https://github.com/mariusschulz/ExtraLINQ)
* Customized for Unity 2017

## Requirement

* Unity 2017

## Install

### With Unity Package Manager

```bash
upm add package dev.upm-packages.extra-zenject
```

Note: `upm` command is provided by [this repository](https://github.com/upm-packages/upm-cli).

You can also edit `Packages/manifest.json` directly.

```jsonc
{
  "dependencies": {
    // (snip)
    "dev.upm-packages.extra-zenject": "[latest version]",
    // (snip)
  },
  "scopedRegistries": [
    {
      "name": "Unofficial Unity Package Manager Registry",
      "url": "https://upm-packages.dev",
      "scopes": [
        "dev.upm-packages"
      ]
    }
  ]
}
```

### Any other else (classical umm style)

```shell
yarn add "umm/extra_linq#^1.0.0"
```

# Usage

* See [README.md](https://github.com/mariusschulz/ExtraLINQ/blob/master/README.md) in original repository.

# License

Copyright (c) 2016 Marius Schulz

Released under the MIT license, see [LICENSE.txt](LICENSE.txt)
