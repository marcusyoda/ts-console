# TS-PRINT
Biblioteca útil para debug em node, com cores e datas formatadas, se propõe a ser intuitiva.

![GitHub package.json version](https://img.shields.io/github/package-json/v/marcusyoda/ts-print)
![Libraries.io dependency status for latest release, scoped npm package](https://img.shields.io/librariesio/release/npm/af-scaffolder) ![npm](https://img.shields.io/npm/dy/ts-print)
[![](https://img.shields.io/github/languages/code-size/badges/shields.svg)](https://github.com/marcusyoda/ts-print)
[![](https://img.shields.io/github/last-commit/google/skia.svg)](https://github.com/marcusyoda/ts-print)
![GitHub Repo stars](https://img.shields.io/github/stars/marcusyoda/ts-print)
![GitHub issues](https://img.shields.io/github/issues/marcusyoda/ts-print)

## TECHNOLOGY:

![LINUX](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![WINDOWS](https://img.shields.io/badge/Windows-navy?style=flat-square&logo=windows&logoColor=white)
![DOCKER](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![TYPESCRIPT](https://img.shields.io/badge/TypeScript-2d79c7?style=flat-square&logo=typescript&logoColor=white)
![JAVASCRIPT](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript&logoColor=yellow)
![NODE](https://img.shields.io/badge/-Nodejs-339933?style=flat-square&logo=Node.js&logoColor=white)


## WHO SHOULD USE:
Any developer who needs clean, well-formatted messages in the terminal.

## GETTING STARTED:
First you need to install with npm or yarn...
```bash
npm install --save ts-print
```

```bash
yarn add ts-print
```

...then you can show any type of message:
```js
import Print from 'ts-print';

Print().br();
Print('Faça ou não faça, tentativa não há!').info();
Print('Faça ou não faça, tentativa não há!').notice();
Print().br();
Print('Faça ou não faça, tentativa não há!').warn();
Print().br();
Print('Faça ou não faça, tentativa não há!').fail();
Print('Faça ou não faça, tentativa não há!').err();
Print().br();
Print('Faça ou não faça, tentativa não há!').success();
Print('Faça ou não faça, tentativa não há!').ok();
Print().br();
```

### PowerShell - Windows 10
Resultado no PowerShell, usando o Windows 10:
![SAMPLE-TERMINAL](https://raw.githubusercontent.com/marcusyoda/ts-print/main/screenshots/powershell-win11-terminal.png)

### PowerShell - Windows 11
Resultado no PowerShell, usando o Windows 11:
![SAMPLE-TERMINAL](https://raw.githubusercontent.com/marcusyoda/ts-print/main/screenshots/powershell-win11-terminal.png)

### bash - Ubuntu 18.04
![SAMPLE-TERMINAL](https://raw.githubusercontent.com/marcusyoda/ts-print/main/screenshots/wsl_ubuntu_18-win11-terminal.png)

## VERSIONING
Versioning [SemVer](http://semver.org/).
To view the available versions, look at: [tags on this repository](https://github.com/marcusyoda/ts-print/tags).

## AUTHOR
* **Marcus Vinícius Mendes Gonçalves - [@marcusyoda](https://github.com/marcusyoda)** - *Prototype development, final version and testing.*

## LICENSE
This project is licensed by MIT. See more at [LICENSE.md](LICENSE.md) for details.
