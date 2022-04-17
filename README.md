## Installation
```cmd
npm install mc-server-stats
```
## Getting Started
Make sure you have installed the latest stable version of [Node.js](https://nodejs.org/en/)
### Using CommonJS
```js
const status = require('mc-server-stats')

status('www.hypixel.net', 25565, output => {
    console.log(output)
})
```
