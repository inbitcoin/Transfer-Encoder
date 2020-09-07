# Transfer-Encoder

> Transfer-Encoder provides the encode/decode functions between a Colored Coins transfer Object to buffer

### Installation

```sh
$ npm install cc-transfer-encoder
```


### Encode

Params:



```js


```

Returns a new Buffer holding the encoded transfer.

##### Example:

```js
var transferEncoder = require('cc-transfer-encoder')


```

### Decode

Params:

- consume - takes a consumable buffer (You can use [buffer-consumer] like in the example to create one)

Returns a Colored Coins payment Object

##### Example:

```js
var transferEncoder = require('cc-transfer-encoder')

```

### Testing

In order to test you need to install [mocha] globaly on your machine

```sh
$ cd /"module-path"/cc-transfer-Encoder
$ mocha
```


## License

This software is licensed under the Apache License, Version 2.0.
See [LICENSE](LICENSE) for the full license text.


[mocha]:https://www.npmjs.com/package/mocha
[buffer-consumer]:https://www.npmjs.com/package/buffer-consumer
