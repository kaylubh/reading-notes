# Cryptography

## Reading Questions

1. **What is the basic principle behind the Caesar Cipher, and how was it used historically?**

    The basic principle of the Caesar Cipher is to shift the letters a number of places in the alphabet. It was used historically to transmit military messages, mainly in the Roman Era.

1. **What are the key differences between symmetric and asymmetric encryption? How is asymmetric used in secure communication today?**

    - Symmetric:
      - Uses a single key to encrypt and decrypt
      - Requires a secure way to share the key
      - Most commonly used in data at rest like hard drives and databases

    - Asymmetric:
      - Uses two different keys for encryption and decryption
      - Public key encrypts, private key decrypts
      - Used primarily for transmitting information, like email and HTTPS

1. **How do computers generate random numbers, and what are the differences between true random number generation (TRNG) and pseudo-random number generation (PRNG)? Discuss their use cases in cryptography.**

    - TRNG:
      - True random number (generation)
      - Uses unpredictable data or entropy
      - Gathers random data from environment
      - Could be based on things like when a user pressed a key, moved a mouse, etc.

    - PRNG:
      - Pseudorandom number (generation)
      - Uses a seed value and an algorithm to create
      - Not secure for use in cryptography unless combined with other methods

1. **What’s the difference between encryption and decryption? Explain with an analogy.**

    Encryption and decryption can be thought of like a puzzle. When you first get a puzzle, all the pieces are jumbled and out of order like encryption. You then put the pieces together to create the resulting image, like decryption.

## Things I want to know more about

- How do public/private keys work?
- What are some common industry standard methods of true random number generation?

## References

- [Khan Academy: Encryption, decryption, and cracking](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/encryption-decryption-and-code-cracking)
- [Wikipedia: Caesar cipher](https://en.wikipedia.org/wiki/Caesar_cipher)
- [Cryptography: Crash Course Computer Science #33](https://www.youtube.com/watch?v=jhXCTbFnK8o)
- [thebestvpn: Introduction to Cryptography](https://thebestvpn.com/cryptography/)
- [How To Geek: How Computers Generate Random Numbers](https://www.howtogeek.com/183051/htg-explains-how-computers-generate-random-numbers/)
