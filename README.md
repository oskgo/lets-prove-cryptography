# lets-prove-cryptography
Alternative to lets-prove-leftpad for cryptographic applications, where the tools do not always support strings and dynamically sized lists and proving things about probabilistic programs is of interest.

We provide two challenges, Modular Multiplication and Xor Coin Toss.

## Modular Multiplication
Using 64 bit operations, implement modular multiplication with 32 bit modulus.
Prove that the image is in the range [0, q) and that the difference between this and regular multiplication is a multiple of the modulus.

## Xor Coin Toss
Implement a sampling algorithm that samples two bits uniformly at random and returns their xor.
Prove that the output is uniformly distributed.
