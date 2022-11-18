# lets-prove-cryptography
Alternative to lets-prove-leftpad for cryptographic applications, where constant-time-ness and probabilistic programs are more interesting than strings.

We provide two challenges, Modular Multiplication and Xor Coin Toss.

## Modular Multiplication
Using 64 bit operations, implement modular multiplication with 32 bit modulus such that the runtime is independent of everything except the modulus.
Prove that the image is in the range [0, q) and that the difference between this and regular multiplication is a multiple of the modulus.

## Xor Coin Toss
Implement a sampling algorithm that samples two bits uniformly at random and returns their xor.
Prove that the output is uniformly distributed.
