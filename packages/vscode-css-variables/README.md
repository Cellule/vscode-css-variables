![Banner](https://github.com/vunguyentuan/vscode-css-variables/raw/master/banner.jpg)

> Working with CSS Variables is a pain, this extension enhances the Web Development experience by providing advanced features such as autocomplete, color preview, and go to definition.

<p align="center">
<a href="https://marketplace.visualstudio.com/items?itemName=vunguyentuan.vscode-css-variables"><img src="https://vsmarketplacebadge.apphb.com/installs-short/vunguyentuan.vscode-css-variables.svg" alt="Installs"/></a>
<a href="https://marketplace.visualstudio.com/items?itemName=vunguyentuan.vscode-css-variables"><img src="https://vsmarketplacebadge.apphb.com/version/vunguyentuan.vscode-css-variables.svg" alt=""/></a>
<a href="https://marketplace.visualstudio.com/items?itemName=vunguyentuan.vscode-css-variables"><img src="https://vsmarketplacebadge.apphb.com/rating-star/vunguyentuan.vscode-css-variables.svg" alt=""/></a>
</p>

## Installation

**[Install via the Visual Studio Code Marketplace →](https://marketplace.visualstudio.com/items?itemName=vunguyentuan.vscode-css-variables)**

By default the extension only scan files with this glob patterns: 

```json
[
	"**/*.css",
	"**/*.scss",
	"**/*.sass",
	"**/*.less"
]
```

And ignore files in these folders:

```json
[
	"**/.git",
	"**/.svn",
	"**/.hg",
	"**/CVS",
	"**/.DS_Store",
	"**/.git",
	"**/node_modules",
	"**/bower_components",
	"**/tmp",
	"**/dist",
	"**/tests"
]
```

## Features
### Autocomplete & Color Preview

Intelligent suggestions for all css variables in the project

<img src="https://github.com/vunguyentuan/vscode-css-variables/raw/master/demo/color_autocomplete.png" alt="" />

### Go to definition

You can easily knows where the variable coming from by hold Alt/Cmd and click to the variable.

<img src="https://github.com/vunguyentuan/vscode-css-variables/raw/master/demo/goto-definition-trim.gif" alt="" />

## Full demo
![Demo](https://github.com/vunguyentuan/vscode-css-variables/raw/master/demo/demo.v2.3.0.gif)
