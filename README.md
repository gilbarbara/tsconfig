# tsconfig [![npm version](https://badge.fury.io/js/%40gilbarbara%2Ftsconfig.svg)](https://badge.fury.io/js/%40gilbarbara%2Ftsconfig)

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
		"outDir": "build",
		"target": "es5",
	}
}
```


## License

MIT