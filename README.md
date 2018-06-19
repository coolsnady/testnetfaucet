# testnetfaucet

testnetfaucet is a simple web app that sends a configurable amount of testnet
coolsnady/hxd via an rpcclient connection to an instance of hxwallet.

## Installation

## Developing

``` bash
git clone https://github.com/coolsnady/hxd/testnetfaucet.git
cd testnetfaucet
dep ensure
go install
```

Start hxwallet with the following options.  

```bash
hxwallet --testnet -u USER -P PASSWORD --rpclisten=127.0.0.1:19111 --rpccert=$HOME/.hxwallet/rpc.cert
```

Configure and start testnetfaucet

```bash
mkdir ~/.testnetfaucet
cp sample-testnetfaucet.conf ~/.testnetfaucet/testnetfaucet.conf (and edit appropriately)
testnetfaucet
```

## Contact

If you have any further questions you can find us at:

- irc.freenode.net (channel #coolsnady/hxd)
- [webchat](https://webchat.freenode.net/?channels=coolsnady/hxd)
- forum.coolsnady/hxd.org
- coolsnady/hxd.slack.com

## Issue Tracker

The
[integrated github issue tracker](https://github.com/coolsnady/hxd/testnetfaucet/issues)
is used for this project.

## License

testnetfaucet is licensed under the [copyfree](http://copyfree.org) ISC License.

