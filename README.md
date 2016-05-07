# Elliptic-Curve
>[Elliptic Curve Cryptography](https://en.wikipedia.org/wiki/Elliptic_curve_cryptography) (ECC) is an approach to public-key cryptography based on the algebraic structure of elliptic curves over finite fields. ECC requires smaller keys compared to non-ECC cryptography (based on plain Galois fields) to provide equivalent security.

This is a JavaScript implementation of ECC in order to help people understand how it works.  To start using it, one must supply 3 variables values: **a**, **b**, and **Z**.  **a** and **b** are coefficients of the Elliptic Curve function that shape the curve.  **Z** is the reduction modulo which is a prime number that acts as the domain of the function in which all values are moduloed by it.

Future plans include to implement the [Diffie-Hellman key exchange](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange) in [conjunction with ECC](https://en.wikipedia.org/wiki/Elliptic_curve_Diffie%E2%80%93Hellman).
