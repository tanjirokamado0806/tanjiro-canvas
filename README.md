## Installation

```bash
$ npm install tanjiro-canvas
```

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
# tanjiro-canvas
