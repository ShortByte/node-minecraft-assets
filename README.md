# node-minecraft-assets
[![NPM version](https://img.shields.io/npm/v/minecraft-assets.svg)](http://npmjs.com/package/minecraft-assets)

[![Try it on gitpod](https://img.shields.io/badge/try-on%20gitpod-brightgreen.svg)](https://gitpod.io/#https://github.com/ShortByte/node-minecraft-assets)

Provide easy access to [minecraft-assets](https://github.com/rom1504/minecraft-assets) in node.js

## Example

```js
const mcAssets=require("minecraft-assets")("1.8.8")

console.log("https://raw.githubusercontent.com/ShortByte/node-minecraft-assets/minecraft-assets/master/data/1.8.8/"+mcAssets.getTexture("wheat_seeds")+".png")

console.log(mcAssets.textureContent["wheat_seeds"].texture)
```

## Documentation

 * See [doc/api.md](doc/api.md)
 * See [doc/history.md](doc/history.md)
 