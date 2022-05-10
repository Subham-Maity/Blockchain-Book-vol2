## I cover all aspects of Blockchain from basic to advanced

# Writer Intro
## I am **[Subham Maity](https://subham-maity.github.io/subham/)**
I love Programming. One of the aims I had when I started ```CodeXam``` was to make learning programming easy.
******************
# Chapter in This Documentation:
* [**1. Why should we study Blockchain?**](#why-should-we-study-blockchain)
* [**2. What is Blockchain Technology?**](#what-is-blockchain-technology)
* [**3. Applications of Blockchain Technology**](#applications-of-blockchain-technology)
* [**4. Blockchain Hashing Algorithm**](#blockchain-hashing-algorithm)
* [**5. Hashing with SHA-256**](#hashing-with-sha-256)
* [**6. Avalanche Effect in Cryptography**](#avalanche-effect-in-cryptography)
* [**7. Blockchain Immutable Ledger**](#blockchain-immutable-ledger)
* [**8. P2P Network**](#p2p-network)
* [**9. Mining in Blockchain**](#mining-in-blockchain)
* [**10. Byzantine Generals Problem**](#the-byzantine-generals-problem)
* [**11. Blockchain Proof of work (Consensus Protocols)**](#blockchain-proof-of-work-and-consensus-protocols)
* [**12. Longest Chain Rule (Competing Chain Problem)**](#longest-chain-rule-and-competing-chain-problems)


******************
******************
******************


# Why should we study Blockchain?

**Look at the image of 2008 financial crisis**

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/2.jpg?raw=true " width="400px"/>
        </p>


**What was the root cause of the global financial crisis in 2008?**

The Biggest Culprit: The Lenders

Most of the blame is on the mortgage originators or the lenders. That's because they were responsible for creating these problems. After all, the lenders were the ones who advanced loans to people with poor credit and a high risk of default

The Global Financial Crisis of 2007-2008 had far-reaching impacts. It catalyzed an implosion of trust in a number of institutions: the commercial banks whose business practices caused the crisis; the central banks that never saw it coming; and the governments that failed to address it effectively or hold the most irresponsible and negligent individuals to account. Indeed, much of the wrongdoing would never have come to light without citizen journalists and whistleblowers. The drawbacks of centralized power became more evident, as did the power of technology.


So we can say ...

<p align="center">
                <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/1.png?raw=true "width="300"/>
                </p>



### Identify the reason why blockchain is the best solution for the future ?

Whenever we purchase something from any website, what do we know, that it will be the same item from the same shop that we ordered. If we donate to any NGO, can we be sure that money is going to that NGO and not to any other? Who is giving that guarantee?

For that purpose, blockchain is the best solution. It is a decentralized system that allows us to store and share data without any middlemen. We are going to share many things later on.

# What is Blockchain Technology?

### Who invented blockchain in 1991?
Stuart Haber and W. Scott Stornetta envisioned what many people have come to know as blockchain, in 1991. Their first work involved working on a cryptographically secured chain of blocks whereby no one could tamper with timestamps of documents.

<p align="center">
                <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/3.png?raw=true " width="300px" />
                </p>

### Satoshi Nakamoto ?

Nakamoto was the one who mined the first blockchain of Bitcoin and was the one who published the whitepaper for the digital currency. Nakamoto had envisioned Bitcoin to be a token of transaction that would be widely adopted by the world to protect against inflation.


<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/4.gif?raw=true "width="300px"/>
        </p>


### What is Blockchain Technology?

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/5.gif?raw=true "  width="400px"/>
        </p>

Blockchain is a distributed ledger that is a collection of records, called blocks, that are linked together by cryptography.


### Example of Blockchain in Real Life

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/6.gif?raw=true "  width="200px"/>
        </p>


Let's say I purchase something from an offline store, and I have a ledger in which I can record the details of the purchase, and that ledger was created by the store. Now if the shopkeeper manipulates the ledger, I can't do anything.


But in the case of blockchain, Shopkeeper can't manipulate the ledger, because the ledger is linked to the blockchain ,and it is immutable.If the shopkeeper try to manipulate the ledger, you can easily find out someone is trying to tamper with the ledger ,and you can easily stop him.

# Applications of Blockchain Technology 

### 1. Product Tracking

Blockchain could also help verify the authenticity of imported raw
materials, such as nuts, cocoa and coffee. "In Denmark, we don't have good
documentation of raw materials we import," Høgh Jensen explained. This is
because long supply chains-where food manufacturers are purchasing
from suppliers rather than primary producers-don't always come with
detailed documentation.

For that reason, blockchain could be used to track the raw materials

**The Technical University of Denmark is developing blockchain solutions for small and medium-sized food manufacturers in an effort to combat food fraud in high-value products.**

### 2. Smart Contracts

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/7.gif?raw=true "  width="200px"/>
        </p>

- smart contracts are a set of rules that are executed by a smart contract

- smart contracts are run on the ethereum blockchain

#### Real World Example
<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/8.jpg?raw=true "  width="200px"/>
        </p>
The shop looks like this – you pay first and then the guy hands you your stuff.

You pay him for the instant noodles, and you find that the shopkeeper just sits back down on his chair and does nothing.

* “Give me the noodles!”

* “Sure, that’ll be ₹20.”

* “I just paid you!”

* “When? No, you didn’t.”

Other than calling the police or starting a fight, you would have no recourse.
<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/9.gif?raw=true "  width="200px"/>
        </p>

The problem here was that you had to trust a human to do his part after you did yours.

While people generally do their part in an implied contract like this one (the contract here was “I give you the stuff after you pay me”), relying on humans to be honest is not an ironclad solution and people get cheated every once in a while.

(Note: Smart contract is just a marketing term for computer programs. It has absolutely nothing to do with a legal contract. Do not relate smart contracts with contracts in a legal sense.)

You would preferably want to take away this element of having to trust this shopkeeper to hold his end of the bargain.

You want to use a system that takes your money and then gives you what you want for sure (a type of contract where you don’t have to trust anybody).

Here, it would be a vending machine.

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/10.gif?raw=true "  width="200px"/>
        </p>


You can buy as many canned slow poisons as you want without having to trust anybody.

You put your money in, you get the stuff you want. You don’t put your money in, you don’t get the stuff you want. You put extra money in, you get change.

You don’t have to trust anybody – it’s an automatic machine that does as it’s programmed to do and nothing else.

(To those of you thinking, what if the machine is malfunctioning – these are all vagaries of the real world. In the world of code, you don’t have to think about this. The program will execute exactly as written.)

The vending machine is a real world example of a smart contract.

It is a software (in this case, real world machinery) executing its code (in this case, giving you the item when you put in money).

That’s it: A smart contract is just a fancy word for a piece of code that automatically executes something in a predetermined way. This piece of code is stored and executed in a distributed/decentralized manner (more on that later).

They are mainly used to reduce the need for a trusted intermediary, disputes, and frauds.

I repeat: it has nothing to do with contracts in the legal sense.

In fact, smart contracts aren’t smart at all. They are just pieces of code that execute exactly as written. For example, if a well-known billionaire is extremely thirsty and offers to pay a million dollars for a drink, it would be smart to take it. But… the vending machine won’t take it, because it hasn’t been explicitly programmed to do so. 

### 3. International Wire Transfer

#### Disadvantages of the centralized banking system:
- Huge fees while transferring money from one bank to another (e.g. $10 for every $1 transferred)
- Time taken to transfer money is long

#### How Blockchain Could Disrupt Banking
Blockchain technology offers a secure and cheap way of sending payments that cuts down on the need for verification from third parties and beats processing times for traditional bank transfers. 90% of members of the European Payments Council believe blockchain technology will fundamentally change the industry by 2025

**Example:** 

Taipei, April 12, 2021 – Global financial services firm J.P. Morgan today announced that it is using blockchain technology to improve funds transfers between banking institutions globally, including payments originating from Taiwan banks to beneficiary banks in other markets. Through improved information exchange related to such payments, the new solution called Confirm is expected to help reduce the number of rejected or returned transactions caused by mismatched payment details, lowering costs for both the sending and receiving banks.

### 4. Healthcare System

Blockchain can be a perfect technology for record-keeping in the medical world. Its applications include sharing healthcare data, keeping electronic healthcare records, managing insurance, and performing administrative tasks. Patients can send their health information via an app to a Blockchain Network.


if that patient store his all medical issue related data store in one block and can be accessed by other hospital and doctor then it save many times and cost.


# Blockchain Hashing Algorithm

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/12.png?raw=true "  width="200px"/>
        </p>

A hash function takes an input string (numbers, alphabets, media files) of any length and transforms it into a fixed length. The fixed bit length can vary (like 32-bit or 64-bit or 128-bit or 256-bit) depending on the hash function which is being used. The fixed-length output is called a hash. This hash is also the cryptographic byproduct of a hash algorithm. We can understand it from the following diagram.


<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/13.png?raw=true "  width="200px"/>
        </p>

The hash algorithm has certain unique properties:

- It produces a unique output (or hash).
- It is a one-way function.


In the context of cryptocurrencies like Bitcoin, the blockchain uses this cryptographic hash function's properties in its consensus mechanism. A cryptographic hash is a digest or digital fingerprints of a certain amount of data. In cryptographic hash functions, the transactions are taken as an input and run through a hashing algorithm which gives an output of a fixed size. The output is called a hash. The hash is then used to verify the integrity of the transaction.'

## SHA-256
A Bitcoin's blockchain uses SHA-256 (Secure Hash Algorithm) hashing algorithm. In 2001, SHA-256 Hashing algorithm was developed by the National Security Agency (NSA) in the USA.
## How does the hashing process works?
Use this website to understand how the hashing process works:

https://passwordsgenerator.net/sha256-hash-generator/

If we type any character in the data section, we will observe its corresponding cryptographic hash in the hash section.
For example: We have type in data section: This is a great tutorial.

It will generate the corresponding Hash:

```
88FBF3D99F89E1252E3FD89FDF4DDEBB474D419237635555222C1905425F08DF
```

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/14.png?raw=true "  width="200px"/>
        </p>

Now if we change the text: "This is a great tutorial." To "this is a great tutorial."

You will find the corresponding Hash:
```
6EED417FA02389F499D3A238AB8365509B21CB65C134A4A7DC8DB1B185C7AEFB
```
In the above, you can see that we have changed only the first character case sentence from capital "T" to small "t" and it will change the whole Hash value.

Since the Hash function is a one-way function, there is no way to get back entire text from the generated hash. This is different from traditional cryptographic functions like encryption where you can encrypt something using the key and by using decryption, you can decrypt the message to its original form.


# Hashing with SHA-256 
Hash functions transform arbitrary large bit strings called messages, into small, fixed-length bit strings called message digests, such that digests identify the messages that produced them with a very high probability. Digests are in that sense fingerprints: a function of the message, simple, yet complex enough that they allow identification of their message, with a very low probability that different messages will share the same digests.

In SHA-256, messages up to 2⁶⁴ bit (2.3 exabytes, or 2.3 billion gigabytes) are transformed into digests of size 256 bits (32 bytes). For perspective, this means that an object 7 times the size of Facebook’s data warehouse in 2014 passed to SHA-256 would produce a chunk of data the size of a 32-letter string of ASCII characters, and that string would the object’s very special fingerprint.

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/15.png?raw=true "  width="200px"/>
        </p>

If we note Bⁿ the set of all bit strings of length strictly n, then we can define SHA-256 as a function from the union of bit strings sets B¹ to B²^⁶⁴, i.e. taking as input any message M of length less than 2⁶⁴, mapping to the bit string set B²⁵⁶, i.e. outputting digests H of length strictly 256.

A prominent use case of hashing is data integrity verification of large files, which relies on the comparison of actual and expected message digests, or checksums. Another is hashing as part of the encryption/decryption journey. Before a message can be encrypted with an algorithm like RSA, it needs to be hashed. In the rest of this article, we explore what hashing does to a message, with a view to later develop a better understanding of RSA.

## Step by step hashing with SHA-256

### Pre-processing

1. Padding. If we note M the message to be hashed, and l its length in bits where l < 2⁶⁴, then as a first step we create the padded message M’, which is message M plus a right padding, such that M’ is of length l’, a multiple of 512. Specifically, we use a padding P such that M’ is:


<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/16.png?raw=true "  width="200px"/>
        </p>

The new message M’=M‖P is of length l’, a multiple of 512. The inclusion of L in padding P helps avoid trivial collisions (i.e. messages “00” and “000” would produce identical padded messages in the absence of L). The original message can be extracted by reading the last 64 for bits for length, and then fetching the message from left to right, of length l.

2. Blocks. M’ is parsed into N blocks of size 512 bits, M¹ to Mᴺ, and each block is expressed as 16 input blocks of size 32 bits, M₀ to M₁₅.
 
<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/17.png?raw=true "  width="200px"/>
        </p>

Each block contains 16 input blocks, numbered from 0 to 15 in every block

3. Hash initialization. The initial hash value H⁰ of length 256 bits (8 input blocks of 32 bits) is set by taking the first 32 bits of the fractional parts of the square roots of the first eight prime numbers:

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/18.png?raw=true "  width="200px"/>
        </p>
The eight input blocks of the initial has value H, in hexadecimal notation

Those values can be reproduced with the below snippet in most browsers and Node ≥8.2.1 (ECMAScript 2017):

```

for (i of [2, 3, 5, 7, 11, 13, 17, 19]) {
  input_block = parseInt((Math.sqrt(i) % 1).toString(2).slice(2, 34), 2);
  console.log(input_block.toString(16), input_block.toString(2).padStart(32, '0'));
}
```

**Algorithm**

The hash is produced by processing each message block Mⁱ of M’ in order. For each of message block Mⁱ:

1. Message schedule. We create a message schedule Wⁱ, consisting of four 512-bit message blocks (each made of 16 input blocks). The first block of Wⁱ is message block Mⁱ, and the next three blocks are variations of Mⁱ, obtained through the formulas in the illustration below:

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/19.png?raw=true "  width="200px"/>
        </p>

In the formulas, t refers to the ‘input block’ number, ranging from 0 to 63. The input blocks of the ‘shuffled blocks’ are functions of prior input blocks, and are generated with special functions, mixing right rotations (ROTR), right shifts (SHR) and exclusive ORs (⊕). Those operations are introduced in a previous article on Bitwise Patterns.

A detail: note that if we align all message schedules Wⁱ vertically, the first column reads from top to bottom as the complete message M’ = M¹‖..‖Mᴺ.


2. The big shuffle. The input blocks of message schedule W are fed, one after the other, to a function represented below as a graph. The graph takes as inputs a hash ωⁱ(t) and a message schedule input block Wⁱ(t), and outputs a hash ωⁱ(t+1). The initial hash ωⁱ(0) fed to the graph is the intermediate hash Hⁱ⁻¹: in the case of W¹, it’s H⁰ defined in the pre-processing step. ωⁱ(0) and Wⁱ(0) produce ωⁱ(1); in turn ωⁱ(1) and Wⁱ(1) produce ωⁱ(2), etc., until ωⁱ(63) is produced.

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/12.gif?raw=true "  width="200px"/>
        </p>

A visual representation the transformations operated on H⁰ using input blocks from the message schedule W. The operation must be repeated 64 times until ω(63) is produced.

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/20.png?raw=true "  width="200px"/>
        </p>

The official loop as seen in FIPS 180–4. a, .., h are initialized as Hi⁻¹(0), .., Hi⁻¹(7). Sigma0, Sigma1, Ch, and Maj are functions using AND, XOR and negations; K is a bit word with 64 input blocks.

3. New hash. After all input blocks from Wⁱ have been used and we ω(63) has been created, we can create the new hash Hⁱ such that each input block of Hⁱ is the sum of the corresponding input block of Hⁱ⁻¹ plus the corresponding input block of ωⁱ(63):

Hⁱ(j) = Hⁱ⁻¹(j) + ωⁱ(63)(j) where + is the addition modulo 2ⁿ

If other message blocks Mⁱ remain, repeat the process (message schedule, big shuffle, creation of the new hash Hⁱ)

If Wⁱ was the last message schedule, then Hⁱ = H is message M’s final hash or digest — its so very special fingerprint.

This concludes the overview of SHA-256 as described in FIPS 180–4. A few closing thoughts:

SHA-256 projects into B²⁵⁶, a space of ~1e77 possible values, which is lots of potential digests: a good thing that provides the intuition that collisions are unlikely
That being said, we do not prove here that collisions are unlikely, we even know they exist given the surjective nature of the hashing function. We know however that (i) given a limited amount of things to hash, we’re unlikely to find collisions (ii) no collisions have been found to date for SHA-256.
Finally, coding your own SHA-256 for production use is probably not a good idea…
…but just for fun and education purposes, here is a version I wrote in JavaScript.

```js
'use strict';

(function (shs) {

  const H0 = [
    0x6a09e667, 0xbb67ae85, 0x3c6ef372, 0xa54ff53a, 0x510e527f, 0x9b05688c, 0x1f83d9ab, 0x5be0cd19,
  ];

  const K = [
    0x428a2f98, 0x71374491, 0xb5c0fbcf, 0xe9b5dba5, 0x3956c25b, 0x59f111f1, 0x923f82a4, 0xab1c5ed5,
    0xd807aa98, 0x12835b01, 0x243185be, 0x550c7dc3, 0x72be5d74, 0x80deb1fe, 0x9bdc06a7, 0xc19bf174,
    0xe49b69c1, 0xefbe4786, 0x0fc19dc6, 0x240ca1cc, 0x2de92c6f, 0x4a7484aa, 0x5cb0a9dc, 0x76f988da,
    0x983e5152, 0xa831c66d, 0xb00327c8, 0xbf597fc7, 0xc6e00bf3, 0xd5a79147, 0x06ca6351, 0x14292967,
    0x27b70a85, 0x2e1b2138, 0x4d2c6dfc, 0x53380d13, 0x650a7354, 0x766a0abb, 0x81c2c92e, 0x92722c85,
    0xa2bfe8a1, 0xa81a664b, 0xc24b8b70, 0xc76c51a3, 0xd192e819, 0xd6990624, 0xf40e3585, 0x106aa070,
    0x19a4c116, 0x1e376c08, 0x2748774c, 0x34b0bcb5, 0x391c0cb3, 0x4ed8aa4a, 0x5b9cca4f, 0x682e6ff3,
    0x748f82ee, 0x78a5636f, 0x84c87814, 0x8cc70208, 0x90befffa, 0xa4506ceb, 0xbef9a3f7, 0xc67178f2,
  ];

  /**
   * Rotate to right
   * @param {number} x - An integer to be shifted right
   * @param {number} n - The number of bits by which to shift
   * @param {string} [w] - The bit notation width. Defaults to x.toString(2).length
   * @return {number} The shifted number
   */
  function rotr(x, n, w) {
    if (!w) { var w = x.toString(2).length; }
    n = n % w;
    return (((x >>> n) | (x << w - n)) >>> 0) % Math.pow(2, w);
  };

  /**
   * Rotate to left
   * @param {number} x - An integer to be shifted right
   * @param {number} n - The number of bits by which to shift
   * @return {number} The shifted number
   */
  function rotl(x, n) {
    let w = x.toString(2).length;
    n = n % w;
    return (((x << n) | (x >>> w - n)) >>> 0) % Math.pow(2, w);
  };

  /**
   * SHA-256 logical functions
   */
  function Ch(x, y, z) { return (x & y) ^ (~x & z); };

  function Maj(x, y, z) { return (x & y) ^ (x & z) ^ (y & z); };

  function Σ0(x) { return rotr(x, 2, 32) ^ rotr(x, 13, 32) ^ rotr(x, 22, 32); };

  function Σ1(x) { return rotr(x, 6, 32) ^ rotr(x, 11, 32) ^ rotr(x, 25, 32); };

  function σ0(x) { return rotr(x, 7, 32) ^ rotr(x, 18, 32) ^ (x >>> 3); };

  function σ1(x) { return rotr(x, 17, 32) ^ rotr(x, 19, 32) ^ (x >>> 10); };

  /**
   * Padding
   * @param {string} m - The message, a binary string (e.g., 011010)
   * @return {string} A padded message
   */
  function pad(m) {
    if (m.length > Math.pow(2, 64)) {
      return console.error('Message out of range.');
    }

    let padding1 = '0'.repeat(512 - ((m.length + 1 + 64) % 512));
    let padding2 = '0'.repeat(64 - m.length.toString(2).length);
    return `${m}1${padding1}${padding2}${m.length.toString(2)}`;
  }

  /**
   * Parse
   * @param {string} paddedMessage - A padded message of length N x 512
   * @return {array} An array containing 512 segments, further split in 32-bit segments
   * expressed as numbers
   */
  function parse(m) {
    let M = m.match(/[0-1]{512}/g);

    return M.map((x) => {
      let arr = x.match(/[0-1]{32}/g);
      return arr.map((x) => {
        return parseInt(x, 2);
      });
    });
  };

  /**
   * Hash
   * @param {string} m - A binary string to be hashed
   * @return {string} A SHA-256 digest
   */
  shs.hash = function (m) {

    // Pre-processing
    let M = parse(pad(m));

    // Initialize the hash
    let H = [H0];

    // Hash computation
    for (let i = 0, N = M.length; i < N; i++) {

      // Prepare the message schedule
      let W = [];
      for (let t = 0; t < 64; t++) {
        if (t <= 15) {
          W[t] = M[i][t];
        } else {
          W[t] = (σ1(W[t - 2]) + W[t - 7] + σ0(W[t - 15]) + W[t - 16]) % Math.pow(2, 32);
        }
      }

      // Initialize the working variables
      let a = H[i][0];
      let b = H[i][1];
      let c = H[i][2];
      let d = H[i][3];
      let e = H[i][4];
      let f = H[i][5];
      let g = H[i][6];
      let h = H[i][7];
      let T1;
      let T2;

      // Do stuff
      for (let t = 0; t < 64; t++) {
        T1 = (h + Σ1(e) + Ch(e, f, g) + K[t] + W[t]) % Math.pow(2, 32);
        T2 = (Σ0(a) + Maj(a, b, c)) % Math.pow(2, 32);
        h = g;
        g = f;
        f = e;
        e = (d + T1) % Math.pow(2, 32);
        d = c;
        c = b;
        b = a;
        a = (T1 + T2) % Math.pow(2, 32);
      }

      // Compute the i-th intermediate hash
      H[i + 1] = [];
      H[i + 1][0] = (a + H[i][0]) % Math.pow(2, 32);
      H[i + 1][1] = (b + H[i][1]) % Math.pow(2, 32);
      H[i + 1][2] = (c + H[i][2]) % Math.pow(2, 32);
      H[i + 1][3] = (d + H[i][3]) % Math.pow(2, 32);
      H[i + 1][4] = (e + H[i][4]) % Math.pow(2, 32);
      H[i + 1][5] = (f + H[i][5]) % Math.pow(2, 32);
      H[i + 1][6] = (g + H[i][6]) % Math.pow(2, 32);
      H[i + 1][7] = (h + H[i][7]) % Math.pow(2, 32);
    }

    let digestWords = H[M.length];
    let digestTemp = digestWords.map((x) => {
      let hex = (x >>> 0).toString(16);
      return `${'0'.repeat(8 - hex.length)}${hex}`;
    });

    let digest = digestTemp.join('');
    return digest;
  };

  /**
   * Hash a UTF-8 string
   * @param {string} string - A string, encoded using UTF-8
   * @return {string} A SHA-256 digest
   */
  shs.hashString = function (str) {
    return shs.hash(helpers.toUTF8OctetString(str).replace(/ /g, '')); // remove whitespqces
  }

}(window.shs = window.shs || {}));
```


```js
'use strict';

(function (helpers) {

  /**
   * Converts binary code point into a UTF-8 binary string
   * @param {number} codepoint - A Unicode codepoint as a number
   * @return {string} The UTF-8 binary string for that codepoint
   */
  function codePointToUtf8BinaryNotation(codePoint) {

    const str = codePoint.toString(2);
    const len = str.length;

    // 0xxxxxxx
    if (len <= 7) {
      let padding = '0'.repeat(7 - len);
      return `0${padding}${str}`;
    }

    // 110xxxxx 10xxxxxx
    else if (len <= 11) {
      let padding = '0'.repeat(11 - len);
      return `110${padding}${str.slice(0, -6)} 10${str.slice(-6)}`;
    }

    // 1110xxxx 10xxxxxx 10xxxxxx
    else if (len <= 16) {
      let padding = '0'.repeat(16 - len);
      return `1110${padding}${str.slice(0, -12)} 10${str.slice(-12, -6)} 10${str.slice(-6)}`;
    }

    // 11110xxx 10xxxxxx 10xxxxxx 10xxxxxx
    else if (len <= 21) {

      // Special case where bits can still fit in the last 3 octets
      if (len == 17) {
        return `11110000 100${str.slice(0, -12)} 10${str.slice(-12, -6)} 10${str.slice(-6)}`;
      }

      let padding = '0'.repeat(21 - len);
      return `11110${padding}${str.slice(0, -18)} 10${str.slice(-18, -12)} 10${str.slice(-12, -6)} 10${str.slice(-6)}`;
    }

    // Error
    else {
      console.error('Did not receive a valid Unicode binaryNotation');
    }

  };

  /**
   * Converts a human-readble string into a UTF-8 binary string
   * @param {string} str - A human-readable string
   * @return {string} An octet string
   */
  helpers.toUTF8OctetString = function (str) {
    let octetStringArray = [];

    // Use for..of to avoid counting of surrogate pairs
    // see: https://mathiasbynens.be/notes/javascript-unicode
    for (let symbol of str) {

      let codePoint = symbol.codePointAt(0);
      let utf8BinaryNotation = codePointToUtf8BinaryNotation(codePoint);

      octetStringArray.push(utf8BinaryNotation);
    };

    return octetStringArray.join(' ');

  };

  /**
   * Converts a UTF-8 octet string in human-readable formate
   * @param {string} str - A UTF-8 octet string in binary format
   * @return {string} A human-readable string
   */
  helpers.fromUTF8OctetString = function (str) {
    let octetStringArray = str.split(' ');
    let i = 0;
    let output = [];

    while (i < octetStringArray.length) {

      // 0xxxxxxx
      if (octetStringArray[i].slice(0, 1) == '0') {
        let codeUnit = octetStringArray.slice(i, i + 1).join(' ');
        let codePointBin = codeUnit.slice(1);
        let codePoint = parseInt(codePointBin, 2);
        output.push(String.fromCodePoint(codePoint));
        i += 1;
      }

      // 110xxxxx 10xxxxxx
      else if (octetStringArray[i].slice(0, 3) == '110') {
        let codeUnit = octetStringArray.slice(i, i + 2).join(' ');
        let codePointBin = `${codeUnit.slice(3, 8)}${codeUnit.slice(11)}`;
        let codePoint = parseInt(codePointBin, 2);
        output.push(String.fromCodePoint(codePoint));
        i += 2;
      }

      // 1110xxxx 10xxxxxx 10xxxxxx
      else if (octetStringArray[i].slice(0, 4) == '1110') {
        let codeUnit = octetStringArray.slice(i, i + 3).join(' ');
        let codePointBin = `${codeUnit.slice(4, 8)}${codeUnit.slice(11, 17)}${codeUnit.slice(20)}`;
        let codePoint = parseInt(codePointBin, 2);
        output.push(String.fromCodePoint(codePoint));
        i += 3;
      }

      // 11110xxx 10xxxxxx 10xxxxxx 10xxxxxx
      else if (octetStringArray[i].slice(0, 5) == '11110') {
        let codeUnit = octetStringArray.slice(i, i + 4).join(' ');
        let codePointBin = `${codeUnit.slice(4, 8)}${codeUnit.slice(11, 17)}${codeUnit.slice(20, 26)}${codeUnit.slice(29)}`;
        let codePoint = parseInt(codePointBin, 2);
        output.push(String.fromCodePoint(codePoint));
        i += 4;
      }

      // Else, there is an error
      else {
        return console.error('Unexpected UTF-8 octet');
      }

    }

    return output.join('');
  };


}(window.helpers = window.helpers || {}));
```
# Avalanche Effect in Cryptography
In cryptography, the avalanche effect is a term associated with a specific behavior of mathematical functions used for encryption. Avalanche effect is considered as one of the desirable property of any encryption algorithm. A slight change in either the key or the plain-text should result in a significant change in the cipher-text. This property is termed as avalanche effect.

In simple words, it quantifies the effect on the cipher-text with respect to the small change made in plain text or the key. 
<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/21.png?raw=true "  width="200px"/>
        </p>

Even though the concept of avalanche effect was identified by “Shannon’s property of confusion”, the term was first mentioned by Horst Feistel. To implement a strong cipher or cryptographic hash function, this should be considered as one of the primary design objective.

In case of algorithm that uses hash value, even a small alteration in an input string should drastically change the hash value. In other words, flipping single bit in input string should at least flip half of the bits in the hash value.

A good encryption algorithm should always satisfy the following relation: 

```
Avalanche effect > 50% 
```

The effect ensures that an attacker cannot easily predict a plain-text through a statistical analysis. An encryption algorithm that doesn’t satisfies this property can favor an easy statistical analysis. That is, if the alteration in a single bit of the input results in change of only single bit of the desired output, then it’s easy to crack the encrypted text.

**Examples:**


**Example-1:** Avalanche effect in cryptography refers

(A) Large changes in cipher text when the keyword is changed minimally

(B) Large changes in cipher text when the plain text is changed

(C) Large impact of keyword change to length of the cipher text

(D) None of the above

Answer: (A)

**Example-2:** Avalanche effect in cryptography

(A) Is desirable property of cryptographic algorithm

(B) Is undesirable property of cryptographic algorithm

(C) Has no effect on encryption algorithm

(D) None of the above

Answer: (A) 

# Blockchain Immutable Ledger

The word Immutable means “cannot be changed.” And ledger is a fancy term for record, a record of something. Therefore an Immutable Ledger is a record that cannot be changed.

In the digital age we need data security and proof that the data has not been altered -- that’s the only way we can trust the digital data.

Such trust and proof of trust is very necessary when we are tracking transactions of money. Imagine if you sent me an electronic funds transfer of $1000 without any proof that you sent it and no way to verify that you sent it. I would not believe you until the money showed up, and if it didn’t show up--what then?

All banks and credit card processing systems use some sort of ledger to keep track of all the transactions that happen. But what if we don’t want to trust a big corporation, bank, or government with our money? Who do we trust?

Blockchain technology introduced the Immutable Ledger. It’s based on math. You put your trust in that math, knowing no one can alter it or change it.

But how does blockchain ensure immutability of the ledger? The foundation is what’s called the hash. The hash is like a digital signature and if a hacker tries to alter anything in the ledger, its hash will change.

Once the hash changes and  no longer matches the previous hash in the ledger, the blockchain will reject that hash (making it null and void like a bad check). The hacker would have to change the next block, and the block after that, and basically the entire blockchain.

They can’t do that because a copy of the blockchain resides on multiple computers around the world. The hacker would need to make all of these changes simultaneously -- hacking into every computer all around the world. This is quite literally impossible. And therefore the ledger becomes immutable -- unable to be changed.


### Example:
<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/23.gif?raw=true "  width="200px"/>
        </p>

Suppose you want to sell your house to someone. Consider the scenario where you sell this property to Mr. ABC and you have all the proofs and records you need to register with the government. And what will the government do here?  Government stores this data in its centralized database. Just imagine if a hacker tampered with the data and somehow manipulated all the records, you would not be able to do anything. Your house would no longer be yours ,and you would be powerless to do anything.

But in that blockchain, the data is immutable. That is, the data is not changed after it is stored in the blockchain.So no one can tamper with the data. If someone tries to tamper with the data, everyone will be notified.


# P2P Network

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/24.gif?raw=true "  width="200px"/>
        </p>

<table style=width:90%><tr><th>S.NO<th>Client-Server Network<th>Peer-to-Peer Network<tr><td>1.<td>In Client-Server Network, Clients and server are differentiated, Specific server and clients are present.<td>In Peer-to-Peer Network, Clients and server are not differentiated.<tr><td>2.<td>Client-Server Network focuses on information sharing.<td>While Peer-to-Peer Network focuses on connectivity.<tr><td>3.<td>In Client-Server Network, Centralized server is used to store the data.<td>While in Peer-to-Peer Network, Each peer has its own data.<tr><td>4.<td>In Client-Server Network, Server respond the services which is request by Client.<td>While in Peer-to-Peer Network, Each and every node can do both request and respond for the services.<tr><td>5.<td>Client-Server Network are costlier than Peer-to-Peer Network.<td>While Peer-to-Peer Network are less costlier than Client-Server Network.<tr><td>6.<td>Client-Server Network are more stable than Peer-to-Peer Network.<td>While Peer-to-Peer Network are less stable if number of peer is increase.<tr><td>7.<td>Client-Server Network is used for both small and large networks.<td>While Peer-to-Peer Network is generally suited for small networks with fewer than 10 computers.</table>


Peer-to-peer, or P2P in its abbreviated form, refers to computer networks using a distributed architecture. In P2P networks, all the computers and devices that are part of them are referred to as peers, and they share and exchange workloads. Each peer in a peer-to-peer network is equal to the other peers. There are no privileged peers, and there is no primary administrator device in the center of the network.   A simulation of a peer-to-peer network A simulation of a peer-to-peer network In a way, peer-to-peer networks are the most egalitarian networks in the computer world. Each peer is equal to the others, and each peer has the same rights and duties as the others. Peers are both clients and servers at the same time.  In fact, every resource and each asset that's available in a peer-to-peer network is shared among peers, without any central server being involved. The shared resources in a P2P network can be things such as processor usage, disk storage capacity, or network bandwidth.


### Example 
Imagine this situation: you open your web browser and visit a website where you download a file. In this case, the website works as a server, and your computer acts as a client receiving the file. You can compare it to a one-way road: the file that you download is a car that goes from point A (the website) to point B (your computer).


Content that's transferred from a network or from the internet to a computer Content that's transferred from a network or from the internet to a computer When you download the same file from a peer-to-peer network, using a BitTorrent platform as a starting point, the download is performed differently. The file is downloaded to your computer in bits and parts that come from many other computers that also connected to the same P2P network and already have that file or at least parts of it. At the same time, the file is also sent (uploaded) from your computer to other devices that are asking for it. This situation is similar to a two-way road: the file is like multiple small cars coming to your PC, while also leaving to others when it is requested. Multiple peers sharing data between themselves


## Why are peer-to-peer networks useful?



P2P networks have some characteristics that make them useful:

- It's hard to take them down. Even if one of the peers is shut down, the others are still operating and communicating. For a P2P (peer-to-peer) network to stop working, you have to close down all its peers.


- Peer-to-peer networks are incredibly scalable. Adding new peers is easy as you don't need to do any central configuration on a central server.


- When it comes to file-sharing, the larger a peer-to-peer network is, the faster it is. Having the same file stored on many of the peers in a P2P network means that when someone needs to download it, the file is downloaded from multiple locations simultaneously.


<h2><span id="Pros_Cons_of_Peer_to_Peer_Model">Pros &amp; Cons of Peer to Peer Model</span></h2>
<table width="624">
<tbody>
<tr>
<td width="312"><strong>Pros</strong></td>
<td width="312"><strong>Cons</strong></td>
</tr>
<tr>
<td width="312">Cheap because it does not need a central server.</td>
<td width="312">It is generally slower because every user is accessed by other users.</p>
<p>&nbsp;</td>
</tr>
<tr>
<td width="312">The network does not need a unique operating system to function.</p>
<p>&nbsp;</td>
<td width="312">Backing up data and archiving is tough because the files are handled by every user, not by a central server.</td>
</tr>
<tr>
<td width="312">The speed of your internet connection may have no bearing on the time it takes for your files to download.</td>
<td width="312">It is less secure than other network models.</p>
<p>&nbsp;</td>
</tr>
<tr>
<td width="312">The system will not be disrupted if one of the computers crashes.</td>
<td width="312">Possibilities of Illegal data sharing.</p>
<p>&nbsp;</td>
</tr>
</tbody>
</table>
<h2><span id="Pros_Cons_of_Client-Server_Model">Pros &amp; Cons of Client-Server Model</span></h2>
<table width="624">
<tbody>
<tr>
<td width="312"><strong>Pros</strong></td>
<td width="312"><strong>Cons</strong></td>
</tr>
<tr>
<td width="312">Authorized users (clients) can access and modify data on a server, allowing for improved sharing.</p>
<p>&nbsp;</td>
<td width="312">When multiple client requests are made at the same time, servers become significantly saturated, resulting in traffic congestion.</td>
</tr>
<tr>
<td width="312">Access and resources are better regulated on servers, ensuring that only authorized clients can acquire or alter data.&nbsp;</td>
<td width="312">This network is vulnerable. If the server crashes, the whole network will collapse.</p>
<p>&nbsp;</td>
</tr>
<tr>
<td width="312">Any new user can be simply integrated into the networks because the network is flexible enough.</td>
<td width="312">Maintaining a central server can be costly and require a lot of manpower and time.</p>
<p>&nbsp;</td>
</tr>
<tr>
<td width="312">Backing up and archiving data is easier in this network.</td>
<td width="312">The user policies in the network must be set by an expert network administrator.</td>
</tr>
</tbody>
</table>


## Example of P2P in Blockchain
As the fundamental element of blockchain technology, P2P architecture manages cryptocurrency transactions. Cryptocurrencies leverage the power of peer-to-peer blockchain technology, as they can be exchanged or transferred without the help of any central body.

A blockchain is a distributed ledger technology which publicly and permanently stores transactions. New “blocks” containing transaction data are continuously linked to the previously filled blocks, forming a chain of data blocks — hence, a blockchain. The blockchain records transactions immutably in digital blocks that contain time-stamped particulars of senders and receivers. With no central authority managing the network, only participating nodes can validate transactions among each other.

When the individual (or group) known as Satoshi Nakamoto developed Bitcoin in 2008, they envisioned creating a “peer-to-peer electronic cash system” that operates in a trustless manner without an intermediary. P2P networks are a key component of blockchain technology, because they support a decentralized ledger of transactions. The system is “trustless,” in that the network’s architecture in itself guarantees the integrity of the transactions.

Here’s where the peer-to-peer blockchain’s basic decentralized conception comes into play. These chains aren’t kept at a centralized location or regulatory server, but are instead dispersed to all the nodes present in the network (even around the globe). As a result, each node holds a copy of the blockchain (and transaction information), thus securing and validating data stored on the network.


# Mining in Blockchain

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/25.gif?raw=true "  width="200px"/>
        </p>

<h2 id="what_is_bitcoin_mining_in_blockchain">What Is Bitcoin Mining in Blockchain?</h2>
<p>Bitcoin mining is the process by which Bitcoin transactions are validated digitally on the Bitcoin network and added to the blockchain ledger. It is done by solving complex cryptographic hash puzzles to verify blocks of transactions that are updated on the decentralized blockchain ledger. Solving these puzzles requires powerful computing power and sophisticated equipment. In return, miners are rewarded with Bitcoin, which is then released into circulation hence the name Bitcoin mining.</p>


<h2 id="bitcoin_vs_traditional_currencies">Bitcoin vs. Traditional Currencies</h2>
<p>While both Bitcoin and traditional currency are similar in that both are a store of value, they differ in many ways. First things first, Bitcoin is the first and most recognized cryptocurrency - a digital currency that is secured by cryptography. Traditional currency, also referred to as fiat money, is a government-issued and regulated currency. </p>
<p>Some differences between Bitcoin and traditional currencies are illustrated in the table below. </p>
<table><tbody>
<tr>
<td></td>
<td>
<h3>Bitcoin </h3>
</td>
<td>
<h3>Traditional Currency </h3>
</td>
</tr>
<tr>
<td>
<p>Tangibility </p>
</td>
<td>
<p>It is a virtual currency and can only be used in its digital form</p>
</td>
<td>
<p>It is a physical currency in the form of notes and coins. However, we can use it in both physical and digital forms</p>
</td>
</tr>
<tr>
<td>
<p>Regulation </p>
</td>
<td>
<p>Issued through mining and controlled by a decentralized distributed network of computers  </p>
</td>
<td>
<p>Issued and controlled by central government authorities, i.e., central banks. Owing to this, the traditional currency is the legal tender in the country governed by the issuing authority. </p>
</td>
</tr>
<tr>
<td>
<p>Governance </p>
</td>
<td>
<p>Governed by a consensus mechanism in which the majority rules </p>
</td>
<td>
<p>Purely governed by the central bank </p>
</td>
</tr>
<tr>
<td>
<p>Value </p>
</td>
<td>
<p>Value is backed by the trust of its users. The more users are willing to transact with Bitcoin, the more stable it becomes.</p>
</td>
<td>
<p>Value is determined by forces of supply and demand and is thus vulnerable to inflation</p>
</td>
</tr>
<tr>
<td>
<p>Supply </p>
</td>
<td>
<p>Capped at 21 million bitcoin </p>
</td>
<td>
<p>Fiat currency has no supply limit </p>
</td>
</tr>
<tr>
<td>
<p>Validation of transactions </p>
</td>
<td>
<p>Bitcoin transactions are validated using blockchain technology and so do not require an intermediary for validation</p>
</td>
<td>
<p>Transactions involve an intermediary such as a bank or a payment provider</p>
</td>
</tr>
<tr>
<td>
<p>Transaction fees </p>
</td>
<td>
<p>Minimal or no associated fees as intermediaries have been eliminated </p>
</td>
<td>
<p>Transactions attract considerable charges </p>
</td>
</tr>
<tr>
<td>
<p>Transaction time and speed </p>
</td>
<td>
<p>The transaction is almost always instantaneous or greatly depends on the network speed </p>
</td>
<td>
<p>Transactions may take time before verification or before they reflect on the system </p>
</td>
</tr>
<tr>
<td>
<p>Security </p>
</td>
<td>
<p>The concepts of decentralization, cryptography, and consensus guarantee a secure network and security of bitcoin transactions</p>
</td>
<td>
<p>Less secure as it can be negatively affected by fluctuations in government policies</p>
</td>
</tr>
<tr>
<td>
<p>Reversals </p>
</td>
<td>
<p>Bitcoin transactions cannot be charged back, reversed, or canceled </p>
</td>
<td>
<p>Chargebacks, reversals, and cancellations are commonplace with traditional currency transactions </p>
</td>
</tr>
</tbody></table>


<h3>The Mining Requirements </h3>

<p>A bitcoin miner will first select their tools of the trade and set them up. These include:</p>
<ul>
<li aria-level="1">Hardware GPU (graphics processing unit), SSD for crypto mining, or ASIC (application-specific integrated circuit) </li>
<li aria-level="1">Mining software </li>
<li aria-level="1">A wallet </li>
<li aria-level="1">Preferred mining pool (if one chooses pool mining option instead of solo mining) </li>
</ul>
<p>Once all these are set up and the system fired up, it performs the mining process autonomously. Any other human involvement comes in the event of system or network failure, power outage, or regular system maintenance. </p>
<ul>
<li aria-level="1">
<h3>Elements of a Bitcoin Transaction </h3>
</li>
</ul>
<p>When a transaction is initiated in the bitcoin network, three elements are involved:</p>
<ul>
<li aria-level="1">A transaction input</li>
<li aria-level="1">A transaction output </li>
<li aria-level="1">The transaction amount </li>
</ul>
<p>For every transaction input, a bitcoin mining software generates a unique cryptographic hash puzzle that is difficult to decode. The software then groups the number of transactions required to form a block into a Merkle tree. </p>
<ul>
<li aria-level="1">
<h3>The Merkle Tree and the SHA-256 Algorithm</h3>
</li>
</ul>
<p>A Merkle tree is a data structure of the hashes in a block and acts as a summary of all the transactions in the block. In the Merkle tree, hashes of individual transactions known as transaction IDs are paired repeatedly using the SHA-256 algorithm until only one hash identifies the entire tree. This hash is known as the Merkle root or root hash. </p>
<p>The Merkle tree enables the efficient verification of transactions in the bitcoin network. </p>

<h2 id="prevention_of_hacking">Prevention of Hacking</h2>
<p>What if someone tries to hack the data? Blockchain, as the name implies, is a chain of blocks—let’s call the blocks A, B and C. Each block has solved a puzzle and generated a hash value of its own, which is its identifier. Now suppose a person tries to tamper with block B and change the data. The data is aggregated in the block, so if the data of the block changes, then the hash value that is the digital signature of the block will also change. It will therefore corrupt the chain after it—the blocks ahead of block B will all get delinked, because the previous hash value of block C will not remain valid.</p>

<p>For a hacker to make the entire blockchain valid for the block B that has been changed, he or she would have to change the hash value of all the blocks ahead of block B. This would require a huge amount of computing power and is next to impossible. With this method, blockchain is non-hackable and prevents data modification.</p>


<h2 id="why_mine_bitcoin">Why Mine Bitcoin?</h2>
<p>Let’s be straight: people primarily mine Bitcoin to earn profits. Other than that, people who are curious about this technology and how it works enjoy experimenting with this relatively new technology.</p>


# The Byzantine Generals Problem
<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/9.jpg?raw=true "  width="200px"/>
        </p>

Imagine that several divisions of the Byzantine army are camped outside an enemy city, each division commanded by its own general. The generals can communicate with one another only by messenger. After observing the enemy, they must decide upon a common plan of action. However, some of the generals may be traitors, trying to prevent the loyal generals from reaching an agreement. The generals must decide on when to attack the city, but they need a strong majority of their army to attack at the same time. The generals must have an algorithm to guarantee that (a) all loyal generals decide upon the same plan of action, and (b) a small number of traitors cannot cause the loyal generals to adopt a bad plan. The loyal generals will all do what the algorithm says they should, but the traitors may do anything they wish. The algorithm must guarantee condition (a) regardless of what the traitors do. The loyal generals should not only reach agreement, but should agree upon a reasonable plan.


Byzantine fault tolerance can be achieved if the correctly working nodes in the network reach an agreement on their values. There can be a default vote value given to missing messages i.e., we can assume that the message from a particular node is ‘faulty’ if the message is not received within a certain time limit. Furthermore, we can also assign a default response if the majority of nodes respond with a correct value.

Leslie Lamport proved that if we have 3m+1 correctly working processors, a consensus(agreement on same state) can be reached if almost m processors are faulty which means that strictly more than two-thirds of the total number of processors should be honest.


# Blockchain Proof of work and Consensus Protocols
Proof of work is the original crypto consensus mechanism, first used by Bitcoin. Proof of work and mining are closely related ideas. The reason it’s called “proof of work” is because the network requires a huge amount of processing power. Proof-of-work blockchains are secured and verified by virtual miners around the world racing to be the first to solve a math puzzle. The winner gets to update the blockchain with the latest verified transactions and is rewarded  by the network with a predetermined amount of crypto.
Proof of work has some powerful advantages, especially for a relatively simple but hugely valuable cryptocurrency like Bitcoin. It’s a proven, robust way of maintaining a secure decentralized blockchain. As the value of a cryptocurrency grows, more miners are incentivized to join the network, increasing its power and security.  Because of the amount of processing power involved, it becomes impractical for any individual or group to meddle with a valuable cryptocurrency’s blockchain.
On the flip side, it’s an energy-intensive process that can have trouble scaling to accommodate the vast number of transactions smart-contract compatible blockchains like Ethereum can generate. And so alternatives have been developed, the most popular of which is called proof of stake.

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/10.jpg?raw=true "  width="200px"/>
        </p>

# Longest Chain Rule and Competing Chain Problems

The chain of blocks that nodes adopt as their blockchain.
The rule that nodes adopt the longest chain of blocks allows every node on the network to agree on what the blockchain looks like, and therefore agree on the same transaction history.
In other words it means that computers acting independently over a network can maintain a globally shared view of a file.

"The proof-of-work chain is the solution to the synchronisation problem, and to knowing what the globally shared view is without having to trust anyone." – Satoshi Nakamoto


The longest chain is the chain of blocks that took the most effort to build.

In short, to add a new block to the blockchain you need to use processing power, which means that every block on the blockchain used up energy to get there.

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/26.gif?raw=true "  width="200px"/>
        </p>


Therefore, a blockchain with more blocks in it will have taken more energy to build than a chain with fewer blocks in it, and as a rule nodes will always adopt this chain over a “shorter” one. 


<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/22.png?raw=true "  width="200px"/>
        </p>


 <p align="center"> Longer chains take more work to build. </p>

As a result, nodes will always adopt the chain that took the most energy to build, which is what we mean when we refer to the “longest chain”.



"The majority decision is represented by the longest chain, which has the greatest proof-of-work effort invested in it." – Satoshi Nakamoto


### Commands
You can see chainwork values for yourself using these bitcoin-cli commands:

#### bitcoin-cli getblockchaininfo
```
$ bitcoin-cli getblockchaininfo   
{
  "chain": "main",
  "blocks": 16069,
  "headers": 16069,
  "bestblockhash": "000000000000000003b9e3bae61fbfa09cf0a60b0e991a14a64a95ef60137003",
  "difficulty": 1.0,
  "mediantime": 1599098365,
  "verificationprogress": 1.0,
  "initialblockdownload": false,
  "chainwork": "0000000000000000000000000000000000000000000000000000000000000002",
  "size_on_disk": 0
}

```

```
$ bitcoin-cli getblockchaininfo                                                         
{
  "chain": "main",
  "blocks": 599501,
  "headers": 599767,
  "bestblockhash": "0000000000000000000cb6141c8076e24f3a1799eef37201634ef392197668f3",
  "difficulty": 13008091666971.9,
  ...
  "chainwork": "0000000000000000000000000000000000000000094b1874d991d4e1fc51005a",
  ...
}

```

#### bitcoin-cli getblock [blockhash]

```
$ bitcoin-cli getblock 00000000b8980ec1fe96bc1b4425788ddc88dd36699521a448ebca2020b38699
{
  "hash": "00000000b8980ec1fe96bc1b4425788ddc88dd36699521a448ebca2020b38699",
  ...
  "height": 12345,
  ...
  "bits": "1d00ffff",
  "difficulty": 1,
  "chainwork": "0000000000000000000000000000000000000000000000000000303a303a303a",
  ...
}
```

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/23.png?raw=true "  width="200px"/>
        </p>

# How mining works
### First we need to know : (Block has a couple of fields: hash, previous hash, timestamp, data, nonce, and a merkle root)
1. A block doesn't store one single transaction. It stores a collection of transactions.

2. A block is mined by a miner.

3. A block contains a collection of transactions. 

4. Each transaction is a collection of inputs and outputs.

5. The inputs are the previous transactions that are used to pay the outputs. 

6. The outputs are the amounts that are being sent to the next transaction. 

7. Block has block number.

<p align="center">
<img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/24.png?raw=true "  width="200px"/>
</p>

###  But there is a another field in a block called nonce.
nonce stands for number used on the once.
everybody changes this nonce field everytime.

suppose nonce is 0.
 
<p align="center">
<img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/25.png?raw=true "  width="200px"/>
</p>

now we put 19 and get a different hash.  then 20 - 21 -22 -23
<p align="center">
<img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/26.png?raw=true "  width="200px"/>
</p>

<p align="center">
<img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/27.png?raw=true "  width="200px"/>
</p>


<p align="center">
<img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/28.png?raw=true "  width="200px"/>
</p>

<p align="center">
<img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/29.png?raw=true "  width="200px"/>
</p>

<p align="center">
<img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/30.png?raw=true "  width="200px"/>
</p>





































# What is Bitcoin?  Bitcoin vs Blockchain 

<p align="center">
        <img src="https://github.com/Subham-Maity/Blockchain-Book-vol2/blob/master/Image%20Ignore/27.gif?raw=true "  width="200px"/>
        </p>

Blockchain is the technology that underpins the cryptocurrency Bitcoin, but Bitcoin is not the only version of a blockchain distributed ledger system in the market. There are several other cryptocurrencies with their own blockchain and distributed ledger architectures.

Meanwhile, the decentralisation of the technology has also led to several schisms or forks within the Bitcoin network, creating offshoots of the ledger where some miners use a blockchain with one set of rules, and others use a blockchain with another set of rules.


### The Bitcoin Original Story 

In late 2008, around the time of the financial crisis, a ground-breaking post appeared on a little-known internet forum entitled Bitcoin: A peer-to-peer electronic cash system. It was written by a mysterious person called Satoshi Nakamoto, a pseudonym used to disguise the author’s true identity.

Satoshi thought that the banks and governments had too much power that they used in their own self-interests. Satoshi envisaged a new type of money called Bitcoin that could change that: a cryptocurrency that wasn’t controlled or run by central banks or governments, that you could send anywhere around the world for free, with no person or institution in charge.

At first nobody paid attention to Satoshi’s wild ideas – but slowly more and more people started buying and using Bitcoin. Many believed it was the future of money, and the worse the big banks behaved the more popular it became.

Since it was formulated and launched in 2009, Bitcoin has grown to a network of around 10,000 “nodes” or participants which use the Proof of Work system to validate transactions and mine bitcoin.

This democracy prevailed until the development of specific mining computers called ASICs which overtook other less powerful machines, and companies began to profit from amassing miners and mining technology. It is still possible for an individual to take part in the Bitcoin process, but it is expensive to set up and the return on investment fluctuates with the highly volatile value of bitcoin itself.

Today, massive mining pools are owned or controlled by large corporations, and power is centralising again. This evolution has somewhat undermined Satoshi’s original vision for blockchain in which the "power” of participants was designed to be evenly distributed - but is now concentrated in the hands of half a dozen mining conglomerates.