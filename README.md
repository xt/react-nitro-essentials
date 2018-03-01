# React Nitro Essentials - Extension Pack for VS Code

Inspired by John Papa's [Angular Essentials](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials), this extension pack for Visual Studio Code adds the necessary extensions that will setup your IDE for getting productive with development in React.

## Recommended Settings

File settings

```json
	"files.autoSave": "afterDelay",
	"files.autoSaveDelay": 2000,
	"files.exclude": {
		"**/.git": true,
		"**/.DS_Store": true,
		"**/*.js": {
			"when": "$(basename).ts"
		},
		"**/*.js.map": {
			"when": "$(basename)"
		}
	},
	"files.hotExit": "onExit",
	"files.defaultLanguage": "typescript",
	"files.trimTrailingWhitespace": true,  
```

Prettier settings

```json
  "prettier.singleQuote": true,
	"prettier.printWidth": 100,
```

## Included

Here is the list of extensions the pack includes:

[React Nitro Snippets](https://marketplace.visualstudio.com/items?itemName=areai51.react-nitro-snippets) - Snippets to accelerate your React App Development.

[ESlint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint into VS Code.

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) VS Code plugin for prettier/prettier, which formats code consistently

[Editor Config](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - EditorConfig for VS Code. Great for maintaining consistent editor settings.

[Chrome Debugger](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) - VS Code debugger for Chrome.

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Visual Studio Code plugin that autocompletes filenames. Hopefully, VS Code will bake this in at some point. Until then, this is a keeper.