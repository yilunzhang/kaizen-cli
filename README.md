<p align=center>
<img src="./assets/title.png">
</p>


<p align=center>
<h1 align=center>KAIZEN CLI</h1>
</p>

<a target="_blank" href="https://circleci.com/gh/PhyrexTsai/kaizen-cli" title="CircleCI"><img src="https://circleci.com/gh/PhyrexTsai/kaizen-cli/tree/master.svg?style=shield"></a>
<a target="_blank" href="https://github.com/PortalNetwork/nifty-game/pulls" title="PRs Welcome"><img src="https://img.shields.io/badge/PRs-welcome-blue.svg"></a>
<a href="#"><img src="https://img.shields.io/hackage-deps/v/lens.svg"/></a>
<a target="_blank" href="#"><img src="https://img.shields.io/github/license/mashape/apistatus.svg"/></a>

> One stop solution for dapp developers

| [English](./README.md) | [한국어](./README_KR.md) | [中文](./README_ZH.md) |

## 🚀 Overview

[![Greenkeeper badge](https://badges.greenkeeper.io/PortalNetwork/kaizen-cli.svg)](https://greenkeeper.io/)

Kaizen is an one stop solution for dapp and dweb developer. With Kaizen, you get:
- Built-in smart contract compilation, linking, deployment and  management.
- Automated code testing with Mocha and Chai.
- Configurable with support technologies for custom build processes.

#### Install
```
npm install -g kaizen-cli 
```

## 🔨 Command Topics

- `kaizen new` - create a dapp template from remote git repository
- `kaizen config` - environment variables of dapps
- `kaizen plugin list` - list all the plugin to dapp
- `kaizen plugin add` - attach an plugin to dapp
- `kaizen plugin remove` - remove an plugin to dapp
- `kaizen build` - scripts used to pack dapp
- `kaizen publish` - scripts used to publish dapp

## 🏗 Usage

![kaizen-cli](./assets/kaizen-cli.png)

#### Create a dapp project

```
kaizen new -n <name> -b <vue|react>
```

## 📣 Contributing
See [CONTRIBUTING.md](./CONTRIBUTING.md) for how to help out.

## 🗒 Licence
See [LICENSE](./LICENSE) for details.
