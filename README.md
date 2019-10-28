Bitcore-NPCcoin Library
=======

A pure and powerful JavaScript NPCcoin library.

## Documentation

The complete docs are hosted here: [bitcore documentation](http://bitcore.io/guide/). There's also a [bitcore API reference](http://bitcore.io/api/) available generated from the JSDocs of the project, where you'll find low-level details on each bitcore utility.

- [Read the Developer Guide](http://bitcore.io/guide/)
- [Read the API Reference](http://bitcore.io/api/)

To get community assistance and ask for help with implementation questions, please use our [community forums](https://forum.bitcore.io/).

## Examples

* [Generate a random address](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#generate-a-random-address)
* [Generate a address from a SHA256 hash](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#generate-a-address-from-a-sha256-hash)
* [Import an address via WIF](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#import-an-address-via-wif)
* [Create a Transaction](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#create-a-transaction)
* [Sign a Dash message](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#sign-a-bitcoin-message)
* [Verify a Dash message](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#verify-a-bitcoin-message)
* [Create an OP RETURN transaction](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#create-an-op-return-transaction)
* [Create a 2-of-3 multisig P2SH address](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#create-a-2-of-3-multisig-p2sh-address)
* [Spend from a 2-of-2 multisig P2SH address](https://github.com/dashpay/bitcore-lib-dash/blob/master/docs/examples.md#spend-from-a-2-of-2-multisig-p2sh-address)


## Security

We're using Bitcore in production, as are [many others](http://bitcore.io#projects), but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.

If you find a security issue, please email security@bitpay.com.

## Contributing

Please send pull requests for bug fixes, code optimization, and ideas for improvement. For more information on how to contribute, please refer to our [CONTRIBUTING](https://github.com/dashpay/bitcore-lib-dash/blob/master/CONTRIBUTING.md) file.

## Building the Browser Bundle

To build a bitcore-lib-dash full bundle for the browser:

```sh
gulp browser
```

This will generate files named `bitcore-lib-npccoin.js` and `bitcore-lib-npccoin.min.js`.

## Development & Tests

```sh
git clone https://github.com/vlddm/bitcore-lib-npccoin
cd bitcore-lib-npccoin
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/dashpay/bitcore-lib-npccoin/blob/master/LICENSE).

Copyright 2013-2015 BitPay, Inc. Bitcore is a trademark maintained by BitPay, Inc.
Copyright 2016 The Dash Foundation, Inc.
