# FLC v2

The Flowchain token (FLC v2) smart contract. This repository hosts the source code for public audits.

# Prerequisites

* [node v10+](https://nodejs.org)\
* [Truffle v5+](https://truffleframework.com)\
* Linux or Mac OS X

# Introduction

The FLC v2 (or the “FLC native token”) is the new update of the original FLC v1 and can be used in Flowchain Network. Please visit the [Flowchain Token](https://flowchain.co/token.html) official website for more information.

FLC v1, as described in its legal opinion report in 2019, is an utility token that can be used in the Flowchain Network. And as an utility token, the FLC v1 token can also be offered to a market for attention, acquisition or consumption. Furthermore, to support Flowchain’s hybrid architecture, FLC requires an off-chain issuable token technology to provide minted token redeem and user withdraw capabilities. 

Thus, an upgrade to the original FLC v1 smart contract shall be applied in prior to the coming Flowchain mainnet launch. For detailed information of FLC v2, please read the official FLC v2 whitepaper: [Off-Chain Issuance of FLC Native Tokens](https://flowchain.co/token.html)

# Development

Install the Truffle toolkit:

```
$ npm install -g truffle
```

Install this project:

```
$ git clone https://github.com/flowchain/flc-v2.git
$ cd flc-v2
$ npm install
```

Compile this project:

```
$ truffle compile
```

Run the migrations:

```
$ truffle migrate
```

To test project contracts, open a new terminal and run the following to start a local Ethereum client:

```
$ truffle develop
```

In the previous terminal, run the following to test contracts:

```
$ truffle test
```

# License

The MIT License

Copyright (c) 2020 The Flowchain Foundation. https://flowchain.co

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.