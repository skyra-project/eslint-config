<div align="center">
  <p>
<h1> @skyra/eslint-config </h1>
<h3> Shareable ESLint config for <a href="https://github.com/skyra-project/skyra">Skyra<a> projects</h3>
<p> Previously known as eslint-config-bamboo 🎋
  </p>

</div>

---

**Table of Contents**

- [Installation](#installation)
- [Usage](#usage)
    + [ESLint config](#eslint-config)
    + [TypeScript config](#typescript-config)
- [Meta](#meta)
  * [License](#license)
  * [Contributing](#contributing)
  * [Buy us some doughnuts](#buy-us-some-doughnuts)
  * [Contributors ✨](#contributors-✨)

---

**Status**

[![GitHub](https://img.shields.io/github/license/skyra-project/eslint-config?logo=github&style=flat-square)](https://github.com/skyra-project/eslint-config/blob/main/LICENSE.md)
[![npm](https://img.shields.io/npm/v/@skyra/eslint-config?color=crimson&logo=npm&style=flat-square)](https://www.npmjs.com/package/@skyra/eslint-config)
[![npm](https://img.shields.io/npm/dt/@skyra/eslint-config?color=crimson&logo=npm&style=flat-square)](https://www.npmjs.com/package/@skyra/eslint-config)

**Bundle Sizes**

[![npm bundle size](https://img.shields.io/bundlephobia/min/@skyra/eslint-config?logo=webpack&style=flat-square)](https://bundlephobia.com/result?p=@skyra/eslint-config)
[![npm bundle size](https://img.shields.io/bundlephobia/minzip/@skyra/eslint-config?logo=webpack&style=flat-square)](https://bundlephobia.com/result?p=@skyra/eslint-config)

**Social Media and Donations**

[![Join Discord server](https://img.shields.io/discord/512303595966824458?color=697EC4&label=Join%20Discord%20Server&logo=discord&logoColor=FDFEFE&style=flat-square)](https://join.skyra.pw)
[![Twitter Follow](https://img.shields.io/twitter/follow/favna_?label=Follow%20@Favna_&logo=twitter&colorB=1DA1F2&style=flat-square)](https://twitter.com/Favna_/follow)
[![Twitter Follow](https://img.shields.io/twitter/follow/kyranet_?label=Follow%20@kyranet_&logo=twitter&colorB=1DA1F2&style=flat-square)](https://twitter.com/kyranet_/follow)
[![Patreon Donate](https://img.shields.io/badge/patreon-donate-brightgreen.svg?label=Donate%20with%20Patreon&logo=patreon&colorB=F96854&style=flat-square&link=https://donate.skyra.pw/patreon)](https://donate.skyra.pw/patreon)
[![PayPal Donate](https://img.shields.io/badge/paypal-donate-brightgreen.svg?label=Donate%20with%20Paypal&logo=paypal&colorB=00457C&style=flat-square&link=https://donate.skyra.pw/paypal)](https://donate.skyra.pw/paypal)

# Installation

**First install the Peer Dependencies**
```sh
yarn add -D eslint typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin
```

**Then install `@skyra/eslint-config`**
```sh
yarn add -D @skyra/eslint-config
```

---

# Usage

### ESLint config

Add the ESLint config to your `package.json`:

```jsonc
{
	"name": "my-project",
	// ...
	"eslintConfig": {
		"extends": "@skyra"
	}
}
```

Or to `eslintrc.js` or `eslintrc.json`:

```json
{
	"extends": "@skyra"
}
```

Create `tsconfig.eslint.json` next to the eslint config file, for example with content:

```json
{
	"extends": "./tsconfig.json",
	"include": ["src", "test"]
}
```

### TypeScript config

You can use `@skyra/eslint-config`'s
[`tsconfig.json`](/tsconfig.json) by extending it in yours:

```json
{
	"extends": "@skyra/eslint-config"
}
```

All of its properties are defaulted for bleeding-edge TypeScript options, you may extend this to include your own
configuration options as well.

# Meta

## License

Copyright © 2020, [Skyra Project](https://github.com/skyra-project).
Released under the [MIT License](LICENSE.md).

## Contributing

1. Fork it!
1. Create your feature branch: `git checkout -b my-new-feature`
1. Commit your changes: `git commit -am 'Add some feature'`
1. Push to the branch: `git push origin my-new-feature`
1. Submit a pull request!

## Buy us some doughnuts

Skyra Project is open source and always will be, even if we don't get donations. That said, we know there are amazing people who
may still want to donate just to show their appreciation. Thanks you very much in advance!

We accept donations through Patreon, BitCoin, Ethereum, and Litecoin. You can use the buttoms below to donate through your method of choice.

| Donate With |         QR         |                                                                  Address                                                                  |
| :---------: | :----------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|   Patreon   | ![PatreonImage][]  |                                               [Click Here](https://www.patreon.com/kyranet)                                               |
|   PayPal    | ![PayPalImage][]   |                [Click Here](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CET28NRZTDQ8L)                |
|   BitCoin   | ![BitcoinImage][]  |         [3JNzCHMTFtxYFWBnVtDM9Tt34zFbKvdwco](bitcoin:3JNzCHMTFtxYFWBnVtDM9Tt34zFbKvdwco?amount=0.01&label=Skyra%20Discord%20Bot)          |
|  Ethereum   | ![EthereumImage][] | [0xcB5EDB76Bc9E389514F905D9680589004C00190c](ethereum:0xcB5EDB76Bc9E389514F905D9680589004C00190c?amount=0.01&label=Skyra%20Discord%20Bot) |
|  Litecoin   | ![LitecoinImage][] |         [MNVT1keYGMfGp7vWmcYjCS8ntU8LNvjnqM](litecoin:MNVT1keYGMfGp7vWmcYjCS8ntU8LNvjnqM?amount=0.01&label=Skyra%20Discord%20Bot)         |

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/kyranet"><img src="https://avatars0.githubusercontent.com/u/24852502?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Antonio Román</b></sub></a><br /><a href="https://github.com/skyra-project/eslint-config/commits?author=kyranet" title="Code">💻</a> <a href="#ideas-kyranet" title="Ideas, Planning, & Feedback">🤔</a> <a href="#projectManagement-kyranet" title="Project Management">📆</a> <a href="https://github.com/skyra-project/eslint-config/commits?author=kyranet" title="Tests">⚠️</a></td>
    <td align="center"><a href="https://favware.tech/"><img src="https://avatars3.githubusercontent.com/u/4019718?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jeroen Claassens</b></sub></a><br /><a href="https://github.com/skyra-project/eslint-config/commits?author=Favna" title="Code">💻</a> <a href="#ideas-Favna" title="Ideas, Planning, & Feedback">🤔</a> <a href="#projectManagement-Favna" title="Project Management">📆</a> <a href="https://github.com/skyra-project/eslint-config/commits?author=Favna" title="Tests">⚠️</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

<!----------------- LINKS --------------->

[patreonimage]:                      https://cdn.skyra.pw/gh-assets/patreon.png
[paypalimage]:                       https://cdn.skyra.pw/gh-assets/paypal.png
[bitcoinimage]:                      https://cdn.skyra.pw/gh-assets/bitcoin.png
[ethereumimage]:                     https://cdn.skyra.pw/gh-assets/ethereum.png
[litecoinimage]:                     https://cdn.skyra.pw/gh-assets/litecoin.png