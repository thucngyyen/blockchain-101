# How mining works: the Nonce

- The _Nonce_ - "the number only used once" is the number that is added into a hash (encrypt) that create a totally different hash value. Different _nonces_ result very different hash values, this is called _Avalanche effect_

- Miner is actually guessing the _nonce_ with the coresponding hash value that meets some specific requirement, ex: hash value need to be smaller than some target hash in order to be consider as "correct hash".

- Because of the _Avalanche effect_, there is no shortcut to find out the _nonce_ quickly beside going over each of the possible value (brute force).