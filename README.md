## Installation

```bash
$ npm install tanjiro-canvas
```
[![NPM version][npm-version-image]][npm-url]
[![NPM downloads][npm-downloads-image]][npm-downloads-url]
[![MIT License][license-image]][license-url]
[![FOSSA Status][fossa-badge-image]][fossa-badge-url]

<p align="center">
    <a href="https://github.com/tanjirokamado0806">
        <img
            src="https://readme-typing-svg.herokuapp.com/?size=15&width=280&lines=Thanks%20Fo%20Using%20Tanjiro%20Canvas"
            alt="404"
        />
    </a>
</p>

## Example Rank Up

```js
const tanjiro = require("tanjiro-canvas");
const  fs = require('fs');

const image = await new tanjiro.RankUp()
    .setAvatar("https://i.postimg.cc/HnkjqLqd/1.jpg")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/cache/rankup.png', data)
 
```
## Rank Up 
<img src="https://i.postimg.cc/VLcT3S29/rankupv2.png" height="145"></img>

## Credits
Remake by [Tanjiro Senpai](https://github.com/tanjirokamado0806)

## License

Tanjiro Canvas is freely distributable under the terms of the [MIT license][license-url].

[![FOSSA Status][fossa-large-image]][fossa-large-url]

[license-image]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE

[npm-url]: https://npmjs.com/package/tanjiro-canvas
[npm-version-image]: https://img.shields.io/npm/v/tanjiro-canvas.svg?style=flat

[npm-downloads-image]: https://img.shields.io/npm/dm/tanjiro-canvas.svg?style=flat
[npm-downloads-url]: https://npmcharts.com/compare/tanjiro-canvas?minimal=true

[fossa-badge-image]: https://app.fossa.com/api/projects/git%2Bgithub.com%2Ftanjirokamado0806%2Ftanjiro-canvas.svg?type=shield
[fossa-badge-url]: https://app.fossa.com/projects/git%2Bgithub.com%2Ftanjirokamado0806%2Ftanjiro-canvas?ref=badge_shield

[fossa-large-image]: https://app.fossa.com/api/projects/git%2Bgithub.com%2Ftanjirokamado0806%2Ftanjiro-canvas.svg?type=large
[fossa-large-url]: https://app.fossa.com/projects/git%2Bgithub.com%2Ftanjirokamado0806%2Ftanjiro-canvas?ref=badge_large
