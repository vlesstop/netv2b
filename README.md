# Netboard

A v2board and sspanel client based on Clash and Electron.

An Electron application with Vue,Pinia,VueRouter and Elemenet-Plus.

![image-20230826105850963](README.assets/image-20230826105850963.png)

Here is the picture of netboard.

## Group

Telegram:https://t.me/TalkToJshi

In addition to the above contact information, there is no others.

**凡是询问项目如何搭建、安装、使用,尤其是英文看不懂等问题，请自觉离开本项目。**

## Donate

Tron(波场):TTTTTTLuVcPQdCsYJuAa13Sc4527wYCZ4D

## IDE Setup

- [VSCode](https://code.visualstudio.com/) + [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) + [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)(Recommened)
- HubuilderX with nothing (author used this)

## Project Setup

### Prepare

First,install nodejs >= 18 via nvm or the package on the [offcial website](https://nodejs.org/).

Second,If you have difficulty accessing the official repository, please install nrm to use the mirror .This is [nrm tutorial](https://doc.houdunren.com/效率提升/7.2 nrm.html#nrm介绍).

Finally ,install pnpm.This is [pnpm tutorial](https://doc.houdunren.com/效率提升/7.1 pnpm.html)

And dont forget to write down your panel in src/renderer/config.json.

```json
{
	"panelUrl":"https://你的网址",
	"panelType":"v2board or metron"
}

```

The default configuration is adjusted for v2board, but if you are metron, please rename" src/renderer/src/metron" to "src/renderer/src/panel" and replace the files in it.

### Install

```bash
$ pnpm install
```

### Development

```bash
$ pnpm dev
```

### Build

```bash
# For windows use pnpm
$ pnpm build:win
# For windows use npm
$ npm run build:win
```

## License

This software is released under the MPL-2.0 license.

## Disclaimers

This program is intended only for the study of computer software architecture, please comply with local laws and regulations.Please note that we are not responsible for your access to information that may not comply with any legal process, regulation, registration or use in your country.

