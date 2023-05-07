# crypto-is-cool
A list of cryptography books, papers, blog posts, presentations, and Q&A answers.

## Books
As the list goes on, the books become increasingly more complicated and mathematical. The first few books are most suitable for developers, and several of the below are free.

- [Real-World Cryptography](https://www.manning.com/books/real-world-cryptography) by [David Wong](https://www.davidwong.fr/)
- [Crypto 101](https://www.crypto101.io/) by [lvh](https://www.lvh.io/)
- [Cryptography Engineering](https://www.schneier.com/books/cryptography-engineering) by [Niels Ferguson](https://en.wikipedia.org/wiki/Niels_Ferguson), [Bruce Schneier](https://www.schneier.com/), and [Tadayoshi Kohno](https://homes.cs.washington.edu/~yoshi/)
- [Crypto Dictionary](https://www.crypto-dictionary.com/) by [Jean-Philippe Aumasson](https://www.aumasson.jp/)
- [Everyday Cryptography](https://www.isg.rhul.ac.uk/~martin/everydaycryptography.html) by [Keith Martin](https://www.isg.rhul.ac.uk/~martin/)
- [Serious Cryptography](https://nostarch.com/seriouscrypto) by [Jean-Philippe Aumasson](https://www.aumasson.jp/)
- [Understanding Cryptography](https://www.crypto-textbook.com/) by [Christof Paar](https://www.crypto-textbook.com/christof_paar.php) and [Jan Pelzl](https://www.crypto-textbook.com/jan_pelzl.php)
- [The Joy of Cryptography](https://joyofcryptography.com/) by [Mike Rosulek](https://web.engr.oregonstate.edu/~rosulekm/)
- [Introduction to Modern Cryptography](https://www.cs.umd.edu/~jkatz/imc.html) by [Jonathan Katz](http://www.cs.umd.edu/~jkatz) and [Yehuda Lindell](http://www.cs.biu.ac.il/~lindell/)
- [A Graduate Course in Applied Cryptography](https://toc.cryptobook.us/) by [Dan Boneh](https://crypto.stanford.edu/~dabo) and [Victor Shoup](https://shoup.net/)

## AEADs
### Commitment
#### Papers
- [Context Discovery and Commitment Attacks How to Break CCM, EAX, SIV, and More](https://eprint.iacr.org/2023/526)
- [Flexible Password-Based Encryption: Securing Cloud Storage and Provably Resisting Partitioning-Oracle Attacks](https://eprint.iacr.org/2023/197)
- [Authenticated Encryption with Key Identification](https://eprint.iacr.org/2022/1680)
- [On Committing Authenticated-Encryption](https://eprint.iacr.org/2022/1260)
- [Efficient Schemes for Committing Authenticated Encryption](https://eprint.iacr.org/2022/268)
- [Actually Good Encryption? Confusing Users by Changing Nonces](https://ethz.ch/content/dam/ethz/special-interest/infk/inst-infsec/appliedcrypto/education/theses/project_MircoStauble.pdf)
- [How to Abuse and Fix Authenticated Encryption Without Key Commitment](https://www.usenix.org/conference/usenixsecurity22/presentation/albertini)
- [Partitioning Oracle Attacks](https://www.usenix.org/conference/usenixsecurity21/presentation/len)
- [Key Committing AEADs](https://eprint.iacr.org/2020/1153)
- [Fast Message Franking: From Invisible Salamanders to Encryptment](https://eprint.iacr.org/2019/016)
- [Message Franking via Committing Authenticated Encryption](https://eprint.iacr.org/2017/664)
- [Security of Symmetric Primitives under Incorrect Usage of Keys](https://eprint.iacr.org/2017/288)

#### Presentations
- [RWC 2023 - Session on Advanced Encryption](https://youtu.be/Xh849Ij3lhU)
- [Asiacrypt 2022 Session on Practical Cryptography 2 - AEAD-KI](https://youtu.be/SQKNpTxPwXE)
- [Efficient Schemes for Committing Authenticated Encryption](https://youtu.be/dZqEtrLh9aM)
- [USENIX Security '22 - How to Abuse and Fix Authenticated Encryption Without Key Commitment](https://youtu.be/VazqgsBwzOY)
- [Partitioning Oracle Attacks](https://youtu.be/h-T1bQTt4_Y)
- [USENIX Security '21 - Partitioning Oracle Attacks](https://youtu.be/j6Q8G3UWHBA)
- [Hunting Invisible Salamanders: Cryptographic (in)Security with Attacker-Controlled Keys](https://youtu.be/1VwC6tZTqIY)
- [Fast Message Franking From Invisible Salamanders to Encryptment](https://youtu.be/3M1jIO-jLHI)
- [Message Franking via Committing Authenticated Encryption](https://youtu.be/ky9nRIl_TqY)

#### IETF
- [Encrypt-then-MAC for Committing AEAD (cAEAD)](https://github.com/samuel-lucas6/draft-lucas-generalised-committing-aead)
- [The AEGIS family of authenticated encryption algorithms](https://datatracker.ietf.org/doc/html/draft-irtf-cfrg-aegis-aead-00#name-introduction-2)
- [Properties of AEAD algorithms](https://www.ietf.org/archive/id/draft-bozhko-cfrg-aead-properties-00.html#name-key-commitment)
- [The OPAQUE Asymmetric PAKE](https://datatracker.ietf.org/doc/html/draft-irtf-cfrg-opaque-06#section-10.3)
- [[Cfrg] Potential vulnerabilities with OPAQUE](https://mailarchive.ietf.org/arch/msg/cfrg/2W9LoeeiRzAiTWVnDsyxvjYPPmo/)

#### Blogs
- [How do I add key commitment to my AEAD scheme in 2023?](https://hybridkey.me/posts/2023-02-07-aead-key-commitment/)
- [Pa(dding|rtitioning) oracles, and another hot take on PAKEs](https://emilymstark.com/2021/02/01/padding-partitioning-oracles-and-another-hot-take-on-pakes.html)
- [Designing New Cryptography for Non-Standard Threat Models](https://soatok.blog/2020/09/09/designing-new-cryptography-for-non-standard-threat-models/)
- [Why I have settled on XChaCha20+Blake3 as the AE suite of choice for my projects](https://mccarty.io/chacha20-blake3/)
- [Threema: Three Strikes, You’re Out](https://soatok.blog/2021/11/05/threema-three-strikes-youre-out/#invisible-salamanders-with-group-messaging)
- [Invisible Salamanders in AES-GCM-SIV](https://keymaterial.net/2020/09/07/invisible-salamanders-in-aes-gcm-siv/)
- [When a KEM is not enough](https://neilmadden.blog/2021/02/16/when-a-kem-is-not-enough/)
- [Lucid Multi-Key Deputies Require Commitment](https://scottarc.blog/2022/10/17/lucid-multi-key-deputies-require-commitment/)
- [libsodium Robustness](https://doc.libsodium.org/secret-key_cryptography/aead#robustness)
- [Improved client-side encryption: Explicit KeyIds and key commitment](https://aws.amazon.com/blogs/security/improved-client-side-encryption-explicit-keyids-and-key-commitment/)

#### Q&A
- [How do I add key commitment to my AEAD scheme in 2023?](https://old.reddit.com/r/crypto/comments/10w1x1k/how_do_i_add_key_commitment_to_my_aead_scheme_in/)
- [Do I need a key committing AEAD to be random key robust?](https://old.reddit.com/r/crypto/comments/opm10n/do_i_need_a_key_committing_aead_to_be_random_key/)
- [Understanding the impact of partitioning oracle attacks on stream ciphers](https://crypto.stackexchange.com/questions/88716/understanding-the-impact-of-partitioning-oracle-attacks-on-stream-ciphers)
- [Understanding the impact of partitioning oracle attacks on production deployments of ChaCha/Salsa](https://old.reddit.com/r/crypto/comments/m0gc2z/understanding_the_impact_of_partitioning_oracle/)
- [My breakdown on Partition Oracle Attacks](https://old.reddit.com/r/crypto/comments/n17k3t/my_breakdown_on_partition_oracle_attacks/)
- [Encrypting h(k) for defeating partition oracle attacks](https://crypto.stackexchange.com/questions/88745/encrypting-hk-for-defeating-partition-oracle-attacks)
- [Do CCM and EAX provide key commitment?](https://crypto.stackexchange.com/questions/87779/do-ccm-and-eax-provide-key-commitment)
- [Encrypt-then-HMAC with a single key is secure?](https://crypto.stackexchange.com/questions/88736/encrypt-then-hmac-with-a-single-key-is-secure)
- [Streaming Interface for authenticated encryption?](https://github.com/LoupVaillant/Monocypher/issues/218)
- [AES-GCM ciphertext that deciphers under two keys](https://crypto.stackexchange.com/questions/84429/aes-gcm-ciphertext-that-deciphers-under-two-keys)
- [Key Committing AES-GCM](https://crypto.stackexchange.com/questions/100699/key-committing-aes-gcm)
- [What is the mathematical property stating that it is hard to find a collision in the AES algorithm?](https://crypto.stackexchange.com/questions/61102/what-is-the-mathematical-property-stating-that-it-is-hard-to-find-a-collision-in)

### AEGIS
#### Papers
- [AEGIS: A Fast Authenticated Encryption Algorithm (v1.1)](https://competitions.cr.yp.to/round3/aegisv11.pdf)
- [Adding more parallelism to the AEGIS authenticated encryption algorithms](https://eprint.iacr.org/2023/523)
- [MILP-based security evaluation for AEGIS/Tiaoxin-346/Rocca](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ise2.12109)
- [Guess-and-Determine Attacks on AEGIS](https://academic.oup.com/comjnl/article-abstract/65/8/2221/6280579?redirectedFrom=fulltext)
- [Weak Keys in Reduced AEGIS and Tiaoxin](https://eprint.iacr.org/2021/187)
- [Analyzing the Linear Keystream Biases in AEGIS](https://tosc.iacr.org/index.php/ToSC/article/view/8468)
- [Linear Biases in AEGIS Keystream](https://eprint.iacr.org/2018/292)
- [Can Caesar Beat Galois?](https://link.springer.com/chapter/10.1007/978-3-319-93387-0_25)

#### IETF
- [draft-irtf-cfrg-aegis-aead - The AEGIS family of authenticated encryption algorithms](https://datatracker.ietf.org/doc/html/draft-irtf-cfrg-aegis-aead)
- [Draft source and issue tracker](https://github.com/jedisct1/draft-aegis-aead)
- [Reference implementations](https://github.com/jedisct1/draft-aegis-aead/tree/main/reference-implementations)
- [AEGIS-128X and AEGIS-256X](https://github.com/jedisct1/aegis-128X)
- [AEGIS-128L and AEGIS-256 MAC](https://github.com/ziglang/zig/pull/13607)

#### Presentations
- [FSE 2022 - Weak Keys in Reduced AEGIS and Tiaoxin](https://youtu.be/KbMaGn1WgTE)
- [FSE 2020 - Analyzing the Linear Keystream Biases in AEGIS](https://youtu.be/tqbhXXu_LBM)
- [CFRG @IETF113](https://datatracker.ietf.org/meeting/113/materials/slides-113-cfrg-aegis-fast-authenticated-encryption-family-00.pdf)
- [DIAC 2016](https://www3.ntu.edu.sg/home/wuhj/research/caesar/aegis/DIAC_2016_AEGIS.pdf)

#### Q&A
- [Should we use the new CAESAR competition ciphers?](https://crypto.stackexchange.com/questions/75293/should-we-use-the-new-caesar-competition-ciphers)
- [Lack of response to CAESAR competition](https://crypto.stackexchange.com/questions/95542/lack-of-response-to-caesar-competition)
- [Rationale for NORX/Ketje/Keyak not being chosen for the CAESAR final portfolio](https://crypto.stackexchange.com/questions/72327/rationale-for-norx-ketje-keyak-not-being-chosen-for-the-caesar-final-portfolio)
- [Side-channel vulnerability of AEGIS naive AES implementation](https://crypto.stackexchange.com/questions/75501/side-channel-vulnerability-of-aegis-naive-aes-implementation)

### Rocca/Rocca-S
#### Papers
- [Rocca: An Efficient AES-based Encryption Scheme for Beyond 5G (Full version)](https://eprint.iacr.org/2022/116)
- [MILP-based security evaluation for AEGIS/Tiaoxin-346/Rocca](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/ise2.12109)
- [Cryptanalysis of Rocca and Feasibility of Its Security Claim](https://tosc.iacr.org/index.php/ToSC/article/view/9852)
- [Differential Fault Attack on Rocca](https://link.springer.com/chapter/10.1007/978-3-031-08896-4_14)
- [Efficient Design Strategies Based on the AES Round Function](https://eprint.iacr.org/2016/299)

#### IETF
- [draft-nakano-rocca-s - Encryption algorithm Rocca-S](https://datatracker.ietf.org/doc/html/draft-nakano-rocca-s)

#### Presentations
- [FSE 2023 - Cryptanalysis of Rocca and Feasibility of Its Security Claim](https://youtu.be/PhDaptX5abg)
- [CFRG@IETF115 - Encryption algorithm Rocca-S](https://datatracker.ietf.org/meeting/115/materials/slides-115-cfrg-rocca-s)
- [FSE 2022 - Rocca: An Efficient AES-based Encryption Scheme for Beyond 5G](https://youtu.be/Zbwu2GQ3ffY)

### ChaCha20-Poly1305
#### Papers
- [The Security of ChaCha20-Poly1305 in the Multi-user Setting](https://eprint.iacr.org/2023/085)
- [A Security Analysis of the Composition of ChaCha20 and Poly1305](https://eprint.iacr.org/2014/613)

#### IETF
- [RFC 8439 - ChaCha20 and Poly1305 for IETF Protocols](https://www.rfc-editor.org/rfc/rfc8439)
- [RFC 8439 Errata](https://www.rfc-editor.org/errata/rfc8439)

#### Blogs
- [Do the ChaCha: better mobile performance with cryptography](https://blog.cloudflare.com/do-the-chacha-better-mobile-performance-with-cryptography/)
- [It takes two to ChaCha (Poly)](https://blog.cloudflare.com/it-takes-two-to-chacha-poly/)
- [ChaCha20 and Poly1305 for TLS](https://www.imperialviolet.org/2013/10/07/chacha20.html)
- [libsodium - ChaCha20-Poly1305](https://doc.libsodium.org/secret-key_cryptography/aead/chacha20-poly1305)

#### Q&A
- [What happens if a nonce is reused in ChaCha20-Poly1305?](https://crypto.stackexchange.com/questions/32075/what-happens-if-a-nonce-is-reused-in-chacha20-poly1305)
- [Does ChaCha20-Poly1305 need random nonce?](https://crypto.stackexchange.com/questions/66799/does-chacha20-poly1305-need-random-nonce)
- [Is ChaCha20 alone sufficient for securing data-at-rest?](https://crypto.stackexchange.com/questions/29280/is-chacha20-alone-sufficient-for-securing-data-at-rest)
- [Stream cipher padding](https://crypto.stackexchange.com/questions/102711/stream-cipher-padding)
- [Should I include the ciphertext length in an AAD when using Chacha20+Poly1205 AEAD?](https://crypto.stackexchange.com/questions/58036/should-i-include-the-ciphertext-length-in-an-aad-when-using-chacha20poly1205-ae)
- [Is streaming API to ChaCha20-Poly1305 possible or recommended against?](https://crypto.stackexchange.com/questions/54541/is-streaming-api-to-chacha20-poly1305-possible-or-recommended-against)
- [chacha20-poly1305 padding and length encoding](https://crypto.stackexchange.com/questions/22489/chacha20-poly1305-padding-and-length-encoding)
- [Understanding ChaCha20-Poly1305 AEAD](https://crypto.stackexchange.com/questions/66450/understanding-chacha20-poly1305-aead)
- [NIST LWC finalists (AEAD) vs ChaCha20-Poly1305](https://crypto.stackexchange.com/questions/89990/nist-lwc-finalists-aead-vs-chacha20-poly1305)

### XChaCha20-Poly1305
#### IETF
- [draft-irtf-cfrg-xchacha - XChaCha: eXtended-nonce ChaCha and AEAD_XChaCha20_Poly1305](https://datatracker.ietf.org/doc/html/draft-irtf-cfrg-xchacha)
- [xchacha-rfc](https://github.com/bikeshedders/xchacha-rfc)

#### Blogs
- [Understanding Extended-Nonce Constructions](https://soatok.blog/2021/03/12/understanding-extended-nonce-constructions/)
- [libsodium XChaCha20-Poly1305 construction](https://doc.libsodium.org/secret-key_cryptography/aead/chacha20-poly1305/xchacha20-poly1305_construction)

#### Q&A
- [Which version of ChaCha is more secure?](https://crypto.stackexchange.com/questions/73220/which-version-of-chacha-is-more-secure)
- [XChaCha20-Poly1305 vs Plain ChaCha20-Poly1305 performance](https://crypto.stackexchange.com/questions/102750/xchacha20-poly1305-vs-plain-chacha20-poly1305-performance)
- [Largest message size for XChaCha20-Poly1305](https://crypto.stackexchange.com/questions/71165/largest-message-size-for-xchacha20-poly1305)
- [Is XChaCha20-Poly1305 nonce misuse-resistant?](https://crypto.stackexchange.com/questions/53153/is-xchacha20-poly1305-nonce-misuse-resistant)
- [Is XChacha20 - Poly1305 Quantum resistant?](https://crypto.stackexchange.com/questions/79518/is-xchacha20-poly1305-quantum-resistant)

## MACs
### HMAC/NMAC
#### Papers
- [Keying Hash Functions for Message Authentication](https://cseweb.ucsd.edu/users/mihir/papers/kmd5.pdf)
- [Message Authentication using Hash Functions - The HMAC Construction](https://cseweb.ucsd.edu/~mihir/papers/hmac-cb.pdf)
- [New Proofs for NMAC and HMAC: Security without Collision-Resistance](https://eprint.iacr.org/2006/043)
- [FIPS PUB 198-1 - The Keyed-Hash Message Authentication Code (HMAC)](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.198-1.pdf) 
- [NIST SP 800-107 - Recommendation for Applications Using Approved Hash Algorithms](https://csrc.nist.gov/publications/detail/sp/800-107/rev-1/final)

#### IETF
- [RFC 2104 - HMAC: Keyed-Hashing for Message Authentication](https://www.rfc-editor.org/rfc/rfc2104)
- [RFC 6151 - Updated Security Considerations for the MD5 Message-Digest and the HMAC-MD5 Algorithms](https://www.rfc-editor.org/rfc/rfc6151)

#### Blogs
- [Canonicalization Attacks Against MACs and Signatures](https://soatok.blog/2021/07/30/canonicalization-attacks-against-macs-and-signatures/)
- [Multiple input MACs](https://neilmadden.blog/2021/10/27/multiple-input-macs/)
- [The Subtle Hazards of Real-World Cryptography](https://soatok.blog/2020/11/27/the-subtle-hazards-of-real-world-cryptography/)
- [HMAC Wear-Out?](https://soatok.blog/2021/08/16/lightning-round/#hmac-wearout)

#### Q&A
- [Why is h(m||k) insecure?](https://crypto.stackexchange.com/questions/5725/why-is-hmk-insecure)
- [Attacks of the MAC construction H(m∥k) for common hashes H?](https://crypto.stackexchange.com/questions/2669/attacks-of-the-mac-construction-mathcalhm-mathbin-k-for-common-hashes)
- [Why is H(k∥x) not a secure MAC construction?](https://crypto.stackexchange.com/questions/1070/why-is-hk-mathbin-vert-x-not-a-secure-mac-construction)
- [Why does a broken hash function undermine an HMAC?](https://crypto.stackexchange.com/questions/2324/why-does-a-broken-hash-function-undermine-an-hmac)
- [Is HMAC-MD5 considered secure for authenticating encrypted data?](https://crypto.stackexchange.com/questions/9336/is-hmac-md5-considered-secure-for-authenticating-encrypted-data)
- [Is HMAC-MD5 still secure for commitment or other common uses?](https://crypto.stackexchange.com/questions/25584/is-hmac-md5-still-secure-for-commitment-or-other-common-uses)
- [Why is HMAC-SHA1 still considered secure?](https://crypto.stackexchange.com/questions/26510/why-is-hmac-sha1-still-considered-secure)
- [Is HMAC prone to birthday attacks?](https://crypto.stackexchange.com/questions/39303/is-hmac-prone-to-birthday-attacks)
- [Length of truncated HMAC output](https://crypto.stackexchange.com/questions/42681/length-of-truncated-hmac-output)
- [Why is a HMAC using a 32bit tag not prone to birthday attacks?](https://crypto.stackexchange.com/questions/41604/why-is-a-hmac-using-a-32bit-tag-not-prone-to-birthday-attacks)
- [CMAC vs HMAC security strength](https://crypto.stackexchange.com/questions/18534/cmac-vs-hmac-security-strength)
- [Is the tag in a MAC scheme a fixed size?](https://crypto.stackexchange.com/questions/88991/is-the-tag-in-a-mac-scheme-a-fixed-size)
- [The difference between MACs vs. HMACs vs. PRFs](https://crypto.stackexchange.com/questions/50860/the-difference-between-macs-vs-hmacs-vs-prfs)
- [Is there any good attack model of HMAC?](https://crypto.stackexchange.com/questions/95568/is-there-any-good-attack-model-of-hmac)
- [Equivalent key size between HMAC and AES?](https://crypto.stackexchange.com/questions/22969/equivalent-key-size-between-hmac-and-aes)
- [With HMAC, can an attacker recover the key, given many known plaintext/tag pairs?](https://crypto.stackexchange.com/questions/8500/with-hmac-can-an-attacker-recover-the-key-given-many-known-plaintext-tag-pairs)
- [Which MAC scheme is quantum resistant?](https://crypto.stackexchange.com/questions/7866/which-mac-scheme-is-quantum-resistant)
- [Can I use HMAC-SHA1 in counter mode to make a stream cipher?](https://crypto.stackexchange.com/questions/12810/can-i-use-hmac-sha1-in-counter-mode-to-make-a-stream-cipher)
- [What is the security strength of an n-bit HMAC?](https://crypto.stackexchange.com/questions/34430/what-is-the-security-strength-of-an-n-bit-hmac)
- [Security of N bit HMAC](https://crypto.stackexchange.com/questions/268/security-of-n-bit-hmac)
- [Purpose of outer key in HMAC](https://crypto.stackexchange.com/questions/3349/purpose-of-outer-key-in-hmac)
- [Keys in HMAC and NMAC](https://crypto.stackexchange.com/questions/27051/keys-in-hmac-and-nmac)
- [What do the magic numbers 0x5c and 0x36 in the opad/ipad calc in HMAC do?](https://crypto.stackexchange.com/questions/3005/what-do-the-magic-numbers-0x5c-and-0x36-in-the-opad-ipad-calc-in-hmac-do)
- [When using AES-256 in combination with HMAC-SHA, should we use SHA-256 or SHA-512?](https://crypto.stackexchange.com/questions/106416/when-using-aes-256-in-combination-with-hmac-sha-should-we-use-sha-256-or-sha-51)
- [Should HMAC-SHA3 be preferred over H(C(k,M))?](https://crypto.stackexchange.com/questions/35127/should-hmac-sha3-be-preferred-over-hck-m)
- [Should HMAC or NMAC or plain Keccak be used for a secure MAC?](https://crypto.stackexchange.com/questions/15741/should-hmac-or-nmac-or-plain-keccak-be-used-for-a-secure-mac)
- [Is HMAC needed for a SHA-3 based MAC?](https://crypto.stackexchange.com/questions/17735/is-hmac-needed-for-a-sha-3-based-mac)
- [Can the HMAC of a pre-hash be considered equivalent to an HMAC of the message?](https://crypto.stackexchange.com/questions/77285/can-the-hmac-of-a-pre-hash-be-considered-equivalent-to-an-hmac-of-the-message)
- [Does having more than one HMAC provide more information to the attacker?](https://crypto.stackexchange.com/questions/106108/does-having-more-than-one-hmac-provide-more-information-to-the-attacker)
- [Side channel security of HMAC in software](https://crypto.stackexchange.com/questions/32325/side-channel-security-of-hmac-in-software)
- [[Cfrg] Related keys in HMAC](https://mailarchive.ietf.org/arch/msg/cfrg/m8rKTuyGYoduFOznrjgIzYXx1LM/)

### Poly1305
#### Papers
- [The Poly1305-AES message-authentication code](https://cr.yp.to/mac/poly1305-20050329.pdf)
- [Cryptography in NaCl](https://cr.yp.to/highspeed/naclcrypto-20090310.pdf)

#### IETF
- [RFC 8439 - ChaCha20 and Poly1305 for IETF Protocols](https://www.rfc-editor.org/rfc/rfc8439)

#### Blogs
- [The design of Poly1305](https://loup-vaillant.fr/tutorials/poly1305-design)
- [libsodium One-time authentication](https://doc.libsodium.org/advanced/poly1305)
- [A state-of-the-art message-authentication code](https://cr.yp.to/mac.html)
- [A Go implementation of Poly1305 that makes sense](https://words.filippo.io/a-literate-go-implementation-of-poly1305/)

#### Q&A
- [Security level of Poly1305 and GMAC](https://crypto.stackexchange.com/questions/94974/security-level-of-poly1305-and-gmac)
- [Poly1305-AES vs AES-GCM](https://crypto.stackexchange.com/questions/43112/poly1305-aes-vs-aes-gcm)
- [What happened to Poly1305AES? Is it obsolete?](https://crypto.stackexchange.com/questions/80155/what-happened-to-poly1305aes-is-it-obsolete)
- [Can Poly1305-AES be used with AES-256?](https://crypto.stackexchange.com/questions/24690/can-poly1305-aes-be-used-with-aes-256)
- [Why is Poly1305 popular given its 'sudden death' properties?](https://crypto.stackexchange.com/questions/20264/why-is-poly1305-popular-given-its-sudden-death-properties)
- [Which algorithm has better performance (HMAC, UMAC, and Poly1305)?](https://crypto.stackexchange.com/questions/56429/which-algorithm-has-better-performance-hmac-umac-and-poly1305)
- [Why not use chacha derivatives (BLAKE, rumba) to make an HMAC for use with chacha? Why use poly1305?](https://crypto.stackexchange.com/questions/75762/why-not-use-chacha-derivatives-blake-rumba-to-make-an-hmac-for-use-with-cha)
- [Do Carter–Wegman MACs allow key reuse if the MAC tag is kept secret?](https://crypto.stackexchange.com/questions/32216/do-carter-wegman-macs-allow-key-reuse-if-the-mac-tag-is-kept-secret)
- [What is the function of the secret key “r” in Poly1305?](https://crypto.stackexchange.com/questions/12071/what-is-the-function-of-the-secret-key-r-in-poly1305)
- [Are poly1305 authenticators distinguishable from random data?](https://crypto.stackexchange.com/questions/17835/are-poly1305-authenticators-distinguishable-from-random-data)
- [Is Poly1305 an information-theoretically secure MAC?](https://crypto.stackexchange.com/questions/48416/is-poly1305-an-information-theoretically-secure-mac)
- [Does Poly1305 have weak keys like GCM/GHASH?](https://crypto.stackexchange.com/questions/94959/does-poly1305-have-weak-keys-like-gcm-ghash)

## KDFs
### HKDF
#### Papers
- [Cryptographic Extraction and Key Derivation: The HKDF Scheme](https://eprint.iacr.org/2010/264)
- [Backdoored Hash Functions: Immunizing HMAC and HKDF](https://eprint.iacr.org/2018/362)

#### IETF
- [RFC 5869 - HMAC-based Extract-and-Expand Key Derivation Function (HKDF)](https://www.rfc-editor.org/rfc/rfc5869)

#### Blogs
- [Understanding HKDF](https://soatok.blog/2021/11/17/understanding-hkdf/)
- [How to use HKDF to derive new keys](https://cendyne.dev/posts/2023-01-30-how-to-use-hkdf.html)
- [Securing HKDF - backdoor resistance using salts](https://hybridkey.me/posts/2018-08-27-securing-hkdf-against-backdoors/)

#### Q&A
- [What is the difference between KDFs for key derivation vs password stretching?](https://crypto.stackexchange.com/questions/40971/what-is-the-difference-between-kdfs-for-key-derivation-vs-password-stretching)
- [Key Derivation Functions vs. Password Hashing Schemes](https://crypto.stackexchange.com/questions/70716/key-derivation-functions-vs-password-hashing-schemes)
- [Why use HKDF for key derivation even it's not time demanding?](https://crypto.stackexchange.com/questions/63754/why-use-hkdf-for-key-derivation-even-its-not-time-demanding)
- [Why do we even need HKDF's?](https://old.reddit.com/r/crypto/comments/wwltjx/why_do_we_even_need_hkdfs/)
- [How is HKDF-Expand better than a simple hash?](https://crypto.stackexchange.com/questions/13232/how-is-hkdf-expand-better-than-a-simple-hash)
- [Choosing between simple Hash and HKDF to derive the second key used for MAC](https://crypto.stackexchange.com/questions/40406/choosing-between-simple-hash-and-hkdf-to-derive-the-second-key-used-for-mac)
- [Is HMAC a suitable substitute for HKDF?](https://crypto.stackexchange.com/questions/58389/is-hmac-a-suitable-substitute-for-hkdf)
- [Differences between HMAC and HKDF in a specific case](https://crypto.stackexchange.com/questions/25988/differences-between-hmac-and-hkdf-in-a-specific-case)
- [Is the output of HKDF uniformly distributed, if my input is not?](https://crypto.stackexchange.com/questions/105953/is-the-output-of-hkdf-uniformly-distributed-if-my-input-is-not)
- [Which risks are associated with deriving multiple keys from the same DH secret Z?](https://crypto.stackexchange.com/questions/5355/which-risks-are-associated-with-deriving-multiple-keys-from-the-same-dh-secret-z)
- [can 32 byte shared secret can be given as input to HKDF-SHA512?](https://crypto.stackexchange.com/questions/101159/can-32-byte-shared-secret-can-be-given-as-input-to-hkdf-sha512)
- [Applications in which you should/shouldn't use a salt with HKDF](https://crypto.stackexchange.com/questions/97975/applications-in-which-you-should-shouldnt-use-a-salt-with-hkdf)
- [What information to include is the 'info' input for HKDF?](https://crypto.stackexchange.com/questions/6553/what-information-to-include-is-the-info-input-for-hkdf)
- [HKDF: ikm, salt and info values](https://crypto.stackexchange.com/questions/64150/hkdf-ikm-salt-and-info-values)
- [HKDF: Difference between salt and info](https://crypto.stackexchange.com/questions/67812/hkdf-difference-between-salt-and-info)
- [HKDF 'salt' and 'info' parameters: Can they be secrets? Should they be?](https://old.reddit.com/r/crypto/comments/10e65t9/hkdf_salt_and_info_parameters_can_they_be_secrets/?rdt=59490)
- [What are the typical input lengths for KDFs?](https://crypto.stackexchange.com/questions/41044/what-are-the-typical-input-lengths-for-kdfs)
- [Minimum length of salt and info for HKDF](https://crypto.stackexchange.com/questions/101163/minimum-length-of-salt-and-info-for-hkdf)
- [Can salt for HKDF be hardcoded within a program](https://crypto.stackexchange.com/questions/101223/can-salt-for-hkdf-be-hardcoded-within-a-program)
- [Generating keys with HKDF from Diffie Hellman agreement](https://crypto.stackexchange.com/questions/10453/generating-keys-with-hkdf-from-diffie-hellman-agreement)
- [Deriving 2 keys using HKDF](https://crypto.stackexchange.com/questions/17830/deriving-2-keys-using-hkdf)
- [multiple keys via HKDF - whats better, one or two applications of HKDF-extract](https://crypto.stackexchange.com/questions/9318/multiple-keys-via-hkdf-whats-better-one-or-two-applications-of-hkdf-extract)
- [repeated use of HKDF-extract on the same PRK](https://crypto.stackexchange.com/questions/9312/repeated-use-of-hkdf-extract-on-the-same-prk)
- [How many different keys can be derived with HKDF before two outputs are identical?](https://crypto.stackexchange.com/questions/88454/how-many-different-keys-can-be-derived-with-hkdf-before-two-outputs-are-identica)
- [Strength of key derived from a hash function considering the birthday attack](https://crypto.stackexchange.com/questions/46468/strength-of-key-derived-from-a-hash-function-considering-the-birthday-attack)
- [Calculate the complexity of HKDF with a 96bit salt and a 128bit key?](https://crypto.stackexchange.com/questions/77768/calculate-the-complexity-of-hkdf-with-a-96bit-salt-and-a-128bit-key)
- [HKDF Bit Security](https://crypto.stackexchange.com/questions/88248/hkdf-bit-security)
- [Security of HKDF when part of output is exposed](https://crypto.stackexchange.com/questions/46449/security-of-hkdf-when-part-of-output-is-exposed)
- [Is HKDF one-way, namely given `Ko` it's hard to guess `Ki`?](https://crypto.stackexchange.com/questions/86464/is-hkdf-one-way-namely-given-ko-its-hard-to-guess-ki)
- [Use of HKDF to get shorter key than digest size](https://crypto.stackexchange.com/questions/100557/use-of-hkdf-to-get-shorter-key-than-digest-size)
- [How to use HKDF to combine two keys](https://crypto.stackexchange.com/questions/12474/how-to-use-hkdf-to-combine-two-keys)
- [Maximum output of HKDF](https://crypto.stackexchange.com/questions/41729/maximum-output-of-hkdf)
- [HKDF-Expand max output length](https://crypto.stackexchange.com/questions/101935/hkdf-expand-max-output-length)
- [Why does HKDF use HMAC(salt, key) instead of HMAC(key, salt)?](https://crypto.stackexchange.com/questions/30459/why-does-hkdf-use-hmacsalt-key-instead-of-hmackey-salt)
- [Why does the RFC version of HKDF-Expand start the counter at 1?](https://crypto.stackexchange.com/questions/100360/why-does-the-rfc-version-of-hkdf-expand-start-the-counter-at-1)
- [Can someone clarify two things about the HKDF by Krawczyk?](https://crypto.stackexchange.com/questions/42272/can-someone-clarify-two-things-about-the-hkdf-by-krawczyk)
- [Difference between RFC-5869 (HKDF) and SP800-108 (Nist's HMAC-based KDF spec)?](https://crypto.stackexchange.com/questions/41245/difference-between-rfc-5869-hkdf-and-sp800-108-nists-hmac-based-kdf-spec)
- [Faster alternative to HKDF](https://crypto.stackexchange.com/questions/31889/faster-alternative-to-hkdf)
- [PBKDF vs HKDF for pretty long key](https://crypto.stackexchange.com/questions/20960/pbkdf-vs-hkdf-for-pretty-long-key)
- [Use of PBKDF2 when no access to HKDF?](https://crypto.stackexchange.com/questions/43933/use-of-pbkdf2-when-no-access-to-hkdf)
- [Is PBKDF2 with 1 iteration acceptable for a simple random key expansion?](https://crypto.stackexchange.com/questions/85855/is-pbkdf2-with-1-iteration-acceptable-for-a-simple-random-key-expansion)
- [Would it be better to use HKDF or SCrypt for deriving a child key?](https://crypto.stackexchange.com/questions/31557/would-it-be-better-to-use-hkdf-or-scrypt-for-deriving-a-child-key)
- [How is key rotation defined?](https://crypto.stackexchange.com/questions/8808/how-is-key-rotation-defined)
- [Why derive keys from a master key instead of generating random keys?](https://crypto.stackexchange.com/questions/67863/why-derive-keys-from-a-master-key-instead-of-generating-random-keys)
- [How to securely combine multiple sources of entropy?](https://crypto.stackexchange.com/questions/42167/how-to-securely-combine-multiple-sources-of-entropy)
