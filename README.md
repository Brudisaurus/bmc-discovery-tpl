# BMC The Pattern Language TPL support in VS Code

[The Pattern Language TPL](https://docs.bmc.com/docs/dosearchsite.action?queryString=The+Pattern+Language+TPL&type=page&where=)

Adds syntax highlighting and snippets The Pattern Language TPL: [tpl](https://docs.bmc.com/docs/discovery/213/the-pattern-language-tpl-1024739589.html) in VS Code
Includes .tpl, .tplpre and .model files support.

Orignally forked from https://github.com/trianglesis/bmc-tpl. Original author: [@trianglesis](https://github.com/trianglesis)


##
- See Docs: [BMC Discovery official documentation page](https://docs.bmc.com/docs/productsupport/bmc-discovery)

- Ask somebody: [BMC Discovery community page](https://community.bmc.com/s/topic/0TO3n000000WJUFGA4/discovery)


## Installation:

- This fork is not publish on vscode yet, but you can build it your self using vsce.

### How to build:
`npm install -g @vscode/vsce`
`vsce package`

####  Set syntax: Ctrl+Shift+P -> "Change language mode" type 'tplpre'

#### Syntax highlighting:

Most of constructions are also checking on integrity,
so if some code will be written on wrong place, highlighting can be broken.


