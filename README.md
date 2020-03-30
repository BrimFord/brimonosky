# brimonosky



HOW TO MAKE DATA MORE SECURE???

# Algorithms
## 1.Triple Data Encryption Standard (TripleDES)
This form of data encryption algorithm applies block cipher algorithms thrice to all the data blocks individually. The magnitude of the key is enlarged to provide extra protection by increasing the encryption ability. Every individual block constitutes of 64-bit data. In this encryption algorithm, three keys are used where each key constitutes of 56 bits. A total of three key permutations are provided under this standard: 
* the three keys are independent
* keys 1 and 2 are independent 
* the three keys are similar

Most importantly, we call #3 triple DES whose key length consists of (3*56 bits = 168 bits) whereas key security consists of (2*56 bits = 112 bits). The substantially longer key length of this type of encryption algorithms overpowers other encryption techniques. Nevertheless, after the development of the advanced encryption standard (AES), TripleDES has been rendered old-fashioned.

## 2.Blowfish Encryption Algorithm
Developed in 1993, the Blowfish encryption algorithm is an alternative for Data Encryption Standard (DES). Before its creation, encryptions were performed by patents and intellectual properties of firms. The developer placed the protocol to the public to make it readily available for any interested user. Compared to DES, it is substantially faster and offers better encryption security. It is an asymmetric type of encryption protocol: uses a single key for both encryption and decryption. Like Twofish, it is a block cipher and its block size is 64-bit and the key size lies anywhere between 32 – 448 bits. It features 18 subkeys, sixteen rounds and has four S-boxes. Its protection capability has been examined and proved. Considering blowfish standard is regarded as a Feistel cipher, a single structure is used to encrypt and decrypt data provided that the reverse direction of the round keys is considered. It is a significantly fast operation because it involves a relatively small number of rounds as well as its clarity of functionality. Nevertheless, its key-scheduling consumes a lot of time, although it has an upper hand when it comes to protecting brute-force threats. Also, its 64-bit block length (size) is rather small making it endangered by birthday attacks compared to AES whose block size is 128 bits and above.

## 3. Twofish Encryption Algorithm
This form of the encryption algorithm is a symmetric key block cipher which is characterized by 128-bit block size and whose keys’ size can run up to 256 bits. This protocol uses one key for encryption and decryption. It is a fast and flexible standard for eight-bit and thirty two-bit CPUs, and small smart cards. The protocol works exemplarily in hardware and has numerous functionality commutations between the speed of encryption and the setup time making it distinctive amongst other protocols. The standard shares some features with its predecessor, blowfish Encryption Algorithm and AES. At one time, this encryption algorithm was a real contestant for the best encryption standard, but the present AES beat it out. This algorithm bears several peculiar characteristics that distinguish it from other standards. First, this cryptographic protocol applies substitution-boxes, S-boxes that are pre-computed and key-reliant. This implies that despite the provision of the S-box, it relies on the cipher key for the decryption of the encrypted data. The significance of the S-box is to conceal the key connection with the ciphertext. Secondly, the Twofish encryption standard is accepted as a substantially secure alternative. Encryption protocols whose keys have 128 bits and above are regarded as safe from attacks: Twofish has a block size of 128 bits. 

## 4. Advanced Encryption Standard (AES)
AES is the most popular and broadly used symmetric encryption standard today. Due to the DES’s small key size and low computing capability, a replacement was required which led to the development of AES. Compared with TripleDES, it has been proved to be more than six times faster. Concerning cybersecurity, the AES acronym, in particular, keeps popping up on all computer screens as it is the world’s most accepted encryption standard. It is seen while using messaging applications such as Signal and Whatsapp, computer platforms such as VeraCrypt and other technologies commonly used. The AES standard constitutes 3 block ciphers where each block cipher uses cryptographic keys to perform data encryption and decryption in a 128-bit block. A single key is used for encryption and decryption thus both the sender and receiver have the same key. The sizes of the keys are considered adequate to secure the classified data to a satisfactory secret level.

## 5. IDEA Encryption Algorithm
The international data encryption algorithm abbreviated as IDEA is a symmetric block cipher data encryption protocol. The key size of the block cipher is 128 bits and is regarded as a substantially secure and one of the best public standards. Of the numerous years, this protocol has been in the market, there is no single attack that has been published in spite of the numerous trials to identify them. The standard was patent in the US and Europe. It is used for non-commercial purposes while commercial authentication can be accessed from Ascom-Tech. Typically, the block cipher runs in round blocks. It applies fifty-two subkeys where each has a 16-bit length. Two subkeys are applied for a single round, four subkeys are applied prior to and after every round. Typically, both the plain text and the ciphertext have equal sizes of 16 bytes. 


## 6. MD5 Encryption Algorithm
This protocol was purposely developed to offer data security as it can take inputs of arbitrary size to generate a 128-bit hash value output. Under this protocol, the encryption technique follows 5 phases where every phase features a predefined task. The five steps include #1, append padding (adding additional bits to the input) bits; #2, append length; #3, initializing MD buffer; #4, message processing; and #5, output. One notable advantage of MD5 is that the protocol allows the generation of a message digest using the initial message. Nevertheless, the protocol is relatively slow.


## 7. HMAC Encryption Algorithm
HMAC stands for hash message authentication code and it is applied to ascertain the message integrity and authenticity. The protocol applies 2 hash computation passes and a cryptographic key. This standard resembles most digital signatures only that symmetric keys are used in HMAC whereas asymmetric types of keys are used in digital signatures.

## 8. RSA Security
This standard offers protection against cyber-attacks by detecting and responding to threats, preventing online fraud, management identification, et al. Its data encryption is founded on the application of both a public key as well as a private key. RSA algorithm generates the two keys simultaneously. When the computer is running on a secure website, the protocol generates a public key that is available publicly for data encryption. On the other hand, the encrypted text is decrypted using the private key. Sender identification is done with the aid of the public key.  

** Briomonosky Project use RSA Security for encrypt your data **

## Techology
* Python 3
* Django or Flask
* Vue JS or native django front-end library
* Circle CI or Travis CI for CI
* 

## Authors
* Brim
* Egor

