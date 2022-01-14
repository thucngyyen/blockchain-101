# How mining works: the Nonce

- The _Nonce_ is "the number only used once" is the number that is added into a hash (encrypt) that create a totally different value. Different value of _nonce_ results in very different hash value, this is called _Avalanche effect_

- Miner is actually guessing the _nonce_ with the coresponding hash value that meets some specific requirement, ex: hash value need to be smaller than some atrribute hash.

- Because of the _Avalanche effect_, there is no shortcut to find out the _nonce_ quickly beside going over each of the possible value (brute force).