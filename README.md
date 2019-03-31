# Secure Hash Standard (SHS) Algorithm (FIPS PUB 180-4) 

### SHA-256
SHA-256 is one of the successor hash functions to SHA-1 (collectively referred to as SHA-2), 
and is one of the strongest hash functions available. SHA-256 is not much more complex to code than SHA-1,
and has not yet been compromised in any way. The 256-bit key makes it a good partner-function for AES. 
It is defined in the NIST (National Institute of Standards and Technology) standard ‘FIPS 180-4’.
NIST also provide a number of test vectors to verify correctness of implementation. There is a good description at Wikipedia.[1]

### Resources
[Algorithm PDF Resource File](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)

### Running the program:

#### Clone my repository:
> git clone https://github.com/irelandeca123/THEORY-OF-ALGORITHMS---SHA-256

#### Compile the script using the GCC Compiler, <sha256> can be changed to whatever you prefer:
> gcc -o <sha256> <sha256.c>

#### Run the script <testingFile> can be changed to the desired .txt file to be tested on:
> /sha256 <testingFile>

### References
[1] - https://www.movable-type.co.uk/scripts/sha256.html
