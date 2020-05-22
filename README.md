# eslint-config-bamboo 🎋

<div align="center">
	<p>
		<a href="https://www.npmjs.com/package/eslint-config-bamboo">
			<img src="https://img.shields.io/npm/v/eslint-config-bamboo.svg?maxAge=3600" alt="NPM version" />
		</a>
		<a href="https://www.npmjs.com/package/eslint-config-bamboo">
			<img src="https://img.shields.io/npm/dt/eslint-config-bamboo.svg?maxAge=3600" alt="NPM downloads" />
		</a>
		<a href="https://dependabot.com">
			<img src="https://api.dependabot.com/badges/status?host=github&repo=kyranet/eslint-config-bamboo" alt="Dependabot Status">
		</a>
		<a href="https://donate.skyra.pw/patreon">
			<img src="https://img.shields.io/badge/donate-patreon-F96854.svg" alt="Patreon" />
		</a>
	</p>
	<p>
		<a href="https://nodei.co/npm/eslint-config-bamboo/"><img src="https://nodei.co/npm/eslint-config-bamboo.png?downloads=true&stars=true" alt="npm install info" /></a>
	</p>
</div>

## Install

```bash
# Install Dependencies
$ yarn add -D eslint typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin

# Install eslint-config-bamboo
$ yarn add -D eslint-config-bamboo
```

## Usage

### ESLint config

Add the ESLint config to your `package.json`:

```jsonc
{
	"name": "my-project",
	// ...
	"eslintConfig": {
		"extends": "bamboo"
	}
}
```

Or to `eslintrc.js` or `eslintrc.json`:

```json
{
	"extends": "bamboo"
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

You can use `eslint-config-bamboo`'s
[`tsconfig.json`](/tsconfig.json) by extending it in yours:

```json
{
	"extends": "eslint-config-bamboo"
}
```

All of its properties are defaulted for bleeding-edge TypeScript options, you may extend this to include your own
configuration options as well.

## Contributing

1. Fork it!
1. Create your feature branch: `git checkout -b my-new-feature`
1. Commit your changes: `git commit -am 'Add some feature'`
1. Push to the branch: `git push origin my-new-feature`
1. Submit a pull request!

## Author

**eslint-config-bamboo** © [kyranet](https://github.com/kyranet), released under the
[MIT](/LICENSE.md) License.
Authored and maintained by kyranet.

> Github [kyranet](https://github.com/kyranet) - Twitter [@kyranet_](https://twitter.com/kyranet_)
