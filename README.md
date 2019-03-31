# Secure Hash Standard (SHS) Algorithm (FIPS PUB 180-4) 

### SHA-256
A cryptographic hash (sometimes called ‘digest’) is a kind of ‘signature’ for a text or a data file. SHA-256 generates an almost-unique 256-bit (32-byte) signature for a text.SHA-256 is one of the successor hash functions to SHA-1 (collectively referred to as SHA-2), 
and is one of the strongest hash functions available. SHA-256 is not much more complex to code than SHA-1,
and has not yet been compromised in any way. The 256-bit key makes it a good partner-function for AES. 
It is defined in the NIST (National Institute of Standards and Technology) standard ‘FIPS 180-4’.
NIST also provide a number of test vectors to verify correctness of implementation.
### Basic operations
 - Boolean operations AND, XOR and OR, denoted by ∧, ⊕ and ∨, respectively.
 - Bitwise complement, denoted by ¯.
 - Integer addition modulo 232, denoted by A + B
- Each of them operates on 32-bit words. For the last operation, binary words are interpreted as
integers written in base 2.
- RotR(A, n) denotes the circular right shift of n bits of the binary word A.
- ShR(A, n) denotes the right shift of n bits of the binary word A.
- AkB denotes the concatenation of the binary words A and B.


#### Resources
[Algorithm PDF Resource File](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)

## Running the program:

#### Clone my repository:
> git clone https://github.com/irelandeca123/THEORY-OF-ALGORITHMS---SHA-256

#### Compile the script using the GCC Compiler, <sha256> can be changed to whatever you prefer:
> gcc -o <sha256> <sha256.c>

#### Run the script < testingFile > which can be changed to the desired .txt file to be tested on:
> ./sha256 < testingFile >

## Program Output
![image](https://raw.githubusercontent.com/irelandeca123/THEORY-OF-ALGORITHMS---SHA-256/master/result.PNG)

### References
-https://www.movable-type.co.uk/scripts/sha256.html

-https://en.wikipedia.org/wiki/SHA-2
