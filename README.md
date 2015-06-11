# Blockchain-Developer-Resources

A list of opininated links to resources useful to blockchain and bitcoin developers

---

## Bitcoin

### Non-technical Introductions

#### Videos
  * [Blockchain University — Bitcoin & the Blockchain: An Introduction](https://www.youtube.com/watch?v=ZUoXUW9zVMs) by [@ChristopherA](https://twitter.com/ChristopherA)

### Technical Introductions

#### Videos
  * 
  
#### Books
  * [Mastering Bitcoin](https://github.com/aantonop/bitcoinbook) by Andreas M. Antonopoulos LLC

### Local-client Javascript Tools & Playgrounds

These tools can be cloned from github to allow you to use your browser to play around with various bitcoin capabilities:

  * [Bip32 Generator](https://github.com/bip32/bip32.github.io) `git clone https://github.com/bip32/bip32.github.io.git ; cd bip32.github.io ; open index.html` lets you create Bip32 Deterministic Heirarchical Keys (prefix xpub* and xprv*) based on a simple brainwallet (aka arbitrary mnemonic) passphrase.
  * [Bip39 Mnemonic Code Converter](https://github.com/dcpos/bip39) `npm install bip39 ; npm run compile` lets you create Bip39 mnemonics (typically 12 words) used for deterministic keys, typically for Bip32.


### Testnet Faucets

You'll need bitcoin testnet coins while developing apps with bitcoin. List in rough order of reliability and number of coins offered.

  * [Sidechains Elements Project Testnet Faucet](https://testnet-faucet.elementsproject.org) - 10 per day per ip

## Javascript & Bitcoin

At Blockchain University we use a number of Javascript based examples to teach the more technical details of Bitcoin. You are not required to have an in-depth knowledge of Javascript, but learning some basics is very useful.

### Setting Up on Mac

If using a Mac, you'll need some basic knowledge how to use the Terminal and the Mac's command line interface, and you'll need to install brew, node and git. A basic tutorial on how to do this is at https://github.com/ChristopherA/intro-mac-command-line

You can also use this script which sets up your Mac automatically, but the above teaches you how do to do it manually https://github.com/blockchainu/prepare-osx-for-blockchain-webdev

### Introduction to Javascript

Javascript is in both server (node) and client (browser) development. Some basics of Javascript are common to both. Here are some resources for learning about Javascript that are generally applicable to both platform.

  * [Learn Javascript](https://www.gitbook.com/book/gitbookio/javascript/details) - a free online book with interactive exercises.

### Introduction to Node & Javascript

Server-based Javascript typically uses Node. These Javascript learning resources are node specific:

  * I like the command-line based [nodeschool.io](http://nodeschool.io) tutorials, as they require you to both use the command line and to create real working code. These are the basic interactive tutorials, but there are many more available.
   * Learn javascripting basics `npm install -g javascripting`
   * Learn Node basics: `npm install -g learnyounode`
   * Learn git: `npm install -g git-it`

### Online courses on Javascript

Most of these courses teach general Javascript, but tend to be more client-side Javascript oriented.

Free online courses:
  * [Code Academy: Javascript](http://www.codecademy.com/tracks/javascript) is an online interactive course that comes highly recommend. The course says 10 hours, but one of our students reported that it took him about 17 hours over 5 days, and found Q&A forum and glossary both helpful.
  * http://javascriptissexy.com/how-to-learn-javascript-properly/
  * http://web.stanford.edu/class/cs101/
  * https://www.udemy.com/refactoru-intro-js/?dtcode=DvGKZ5c30m1I

Some non-free online courses:
  * http://www.lynda.com/JavaScript-tutorials/Nodejs-Essential-Training/141132-2.html
  * https://www.udemy.com/courses/search?ref=home&q=javascript

### General Javascript Books and eBooks

Some general Javascript online books in eBook (in rough order of preference)

http://eloquentjavascript.net
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
http://bonsaiden.github.io/JavaScript-Garden/

---
## Bitcoin Standards

* BIP32 - Bitcoin Deterministic Heirarchical Keys
  * Good article on [Deterministic Wallets](http://blog.richardkiss.com/?p=313)
  * Discussion of [BIP32 Advantages and Flaws](https://bitcoinmagazine.com/8396/deterministic-wallets-advantages-flaw/)
  * The [BIP0032 Standard](https://en.bitcoin.it/wiki/BIP_0032)
  * [Bip32 Generator](https://github.com/bip32/bip32.github.io) `git clone https://github.com/bip32/bip32.github.io.git ; cd bip32.github.io ; open index.html` lets you create Bip32 Deterministic Heirarchical Keys (prefix xpub* and xprv*) based on a simple brainwallet (aka arbitrary mnemonic) passphrase.


---

## Sidechains

Sidechains are new blockchains, but are backed by Bitcoin rather than being an altcoin. Using "two-way pegging" these sidechains provide a method for developers to make changes and play around with blockchain rules in a separate blockchain, while keeping these coins linked to Bitcoin.

### Introduction
  * [Ask Dr. Bitcoin: What are Side-Chains](http://siliconangle.com/blog/2014/04/21/bitcoin-sidechains/)

### Concepts
  * The Initial Two-Way Pegging [proposal](http://sourceforge.net/p/bitcoin/mailman/message/32108143/) by Adam Back
  * Blockstream Whitepaper [Enabling Blockchain Innovations with Pegged Sidechains](https://www.blockstream.com/sidechains.pdf)

### Projects
  * [Sidechain Elements Project] (https://github.com/ElementsProject/elementsproject.github.io/) - Open source github project investigating and experiment with various bitcoin sidechain concepts
