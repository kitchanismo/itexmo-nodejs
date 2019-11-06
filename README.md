# ITEXMO

The [ITEXMO](https://itexmo.com/) library exported as [Node.js](https://nodejs.org/) modules.

## Installation

Using npm:

```shell
$ npm i --save itexmo
```

In Node.js:

```js
// add another config:
// parameters: priority String, senderID String and server String
const itexmo = require('itexmo')({ apiCode: 'YOUR_API_CODE' })

itexmo
  .send({ to: '+63xxxxxxxxx', body: 'hello world' })
  .then(message => console.log(message))
  .catch(err => console.log(err))
```
