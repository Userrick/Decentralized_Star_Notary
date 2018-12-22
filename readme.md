
# Decentralized Star Notary (UDACITY)


## Project overview


The goal of the project was to buld a Decentralized Star Notary (dApp) with Truffle.

## Project specification

https://review.udacity.com/#!/rubrics/2297/view

---


## My contract and the transaction

My contract
```
  0x6Ccbe5Fa703BC7fb6Fafca25F79ed5e83D851c92
```
Transaction Hash
```
  0x11a3711bfe4f13a766df76e3366df275c4feb85ced4b96fb937c5bb25092b2dc
```
My account on rinkeby
```
  0x0be3dCDC09881e9e0773ce9287061Ff803A38d3d
```

## Getting started

Open a command prompt or shell terminal after install node.js and execute:

```
  npm install
```
```
  npm install -g truffle
```

## Testing local

1) Download Ganache from here: https://truffleframework.com/ganache
2) Run Ganache
3) Open Command line and got to your project directory
4) git clone [This_Repository]
5) Change the API of infurs + the mnemonic in the truffle-config.js to yours
5) Enter following commands when in smart_contracts folder:
```
  truffle develop
```
```
  compile
```
```
  migrate
```

## Deployment on rinkeby and test locally with contract on test net

```
  truffle migrate --reset --network rinkeby
```
```
  enter your hash of your contract into the index.html
```
```
  npm live-server
```
```
  live-server
```

## App Info

### Author

Rick Warling

### Version

1.0.0

## Sources which helped me:

Credits to:

- Udacity Project5 Concepts section
- Udacity slack of nanodegree
