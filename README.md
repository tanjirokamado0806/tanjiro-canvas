## Installation

```bash
$ npm install tanjiro-canvas-beta
```

## Example GoodBye

```js
const tanjiro = require("tanjiro-canvas-beta"),
const  fs = require('fs');

const image = await new tanjiro.Goodbye()
    .setUsername("Tanjiro")
    .setGuildName("Demon Slayer")
    .setGuildIcon("https://i.postimg.cc/HnkjqLqd/1.jpg")
    .setMemberCount("404")
    .setAvatar("https://graph.facebook.com/100080302688386/picture?width=512&height=512&access_token=6628568379%7Cc1e620fa708a1d5696fb991c1bde5662")
    .setBackground("https://i.postimg.cc/XqSg4B3w/6500892.jpg")
    .toAttachment();
  
  data = image.toBuffer();
  await fs.writeFileSync(__path +'/cache/bye.png', data)
 
```
## IMAGE 
<img src="https://graph.facebook.com/100080302688386/picture?width=512&height=512&access_token=6628568379%7Cc1e620fa708a1d5696fb991c1bde5662" height="145"></img>

## Credits
Remake by [Tanjiro Senpai](https://github.com/tanjirokamado08)
# tanjiro-canvas-beta
# tanjiro-canvas-beta
