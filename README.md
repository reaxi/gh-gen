# gh-gen

[<img alt="npm" src="https://img.shields.io/npm/dt/wksp?logo=npm">](https://npmjs.com/package/gh-gen)
<img alt="Maintained" src="https://img.shields.io/maintenance/yes/2023">

**gen**erate apps from any **g**it**h**ub repository

> like starters, templates and more

> yarn berry support, `-2` or `--berry`

## Usage

```
gh-gen user/repo
```

```
gh-gen user/repo [templates/hello]
```

> like templates/ or examples/ (any folder path)

```
gh-gen user/repo -n name -b branch
```

> use specific branch

### aliases

-   aliases: pick user/repo and branch

default aliases:

-   `npr`: Andrew-Colman/node-package-rollup
-   `next`: Andrew-Colman/next.ts

## options

```ts

argument: '[repo]',
"the repository to generate, please use this signature: 'user/repo' or an known alias"


option: '-p, --path <path>' // path

option: '-b, --branch <name> ', // 'repository branch'

option: '-n, --name <name>', // 'project name (as in package.json)'

option: '-v, --version <version>', // 'project version (as in package.json)'

option: '-a, --author <author>', // 'project author (as in package.json)'

option: '-p, --path <path>', // 'project path'

option: '-2, --berry [ide]', // 'start a yarn/berry project' // ide: vscode (will install vscode sdk for berry)

option: '--aliases', // 'list all aliases from gh-gen-alises.json' //standalone option

option: '-d, --debug', // 'enable debug mode'
```
