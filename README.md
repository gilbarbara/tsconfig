# tsconfig

Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

## Install

```
$ npm install --save-dev @gilbarbara/tsconfig
```


## Usage

`tsconfig.json`

```json
{
	"extends": "@gilbarbara/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "es2018",
		"lib": [
			"es2018"
		]
	}
}
```


## License

MIT