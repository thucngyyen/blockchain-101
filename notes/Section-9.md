# Hash SHA256

The SHA256 Hash Algorithm has 5 requirements:
1. One-Way: can't be reverse
2. Deterministic: always result the same hash from similar doc
3. Fast Computation: gotta be fast
4. The Avalanche Effect: if the **nonce** (discussed later) changes, it will change the whole hash

    Eg: SHA256(doc, nonce) = hash

5. Must withstand collisions: collections are acceptable but the algorithm has to withstand