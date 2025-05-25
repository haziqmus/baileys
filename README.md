# <div align='center'>Baileys - Typescript/Javascript WhatsApp Web API</div>

<div align="center"><img src="https://raw.githubusercontent.com/WhiskeySockets/Baileys/refs/heads/master/Media/logo.png"></div>

## Important Note

The original repository was initially removed by its creator and subsequently taken over by [WhiskeySockets](https://github.com/WhiskeySockets). Building upon this foundation, I have implemented several enhancements and introduced new features that were not present in the original repository. These improvements aim to elevate functionality and provide a more robust and versatile experience.

## Install

Install in package.json:
```json
"dependencies": {
    "baileys": "github:haziqmus/baileys"
}
```
or install in terminal:
```
npm install baileys@github:haziqmus/baileys
```

Then import the default function in your code:
```ts 
// type esm
import makeWASocket from 'baileys'
```

```js
// type cjs
const { default: makeWASocket } = require("baileys")
```