# crypto-is-cool
A list of cryptography books, papers, blog posts, presentations, and Q&A answers.

## Books
As the list goes on, the books become increasingly more complicated and mathematical. The first few books are most suitable for developers, and several of the below are free.

- [Real-World Cryptography](https://www.manning.com/books/real-world-cryptography) by [David Wong](https://www.davidwong.fr/)
- [Crypto 101](https://www.crypto101.io/) by [lvh](https://www.lvh.io/)
- [Cryptography Engineering](https://www.schneier.com/books/cryptography-engineering) by [Niels Ferguson](https://en.wikipedia.org/wiki/Niels_Ferguson), [Bruce Schneier](https://www.schneier.com/), and [Tadayoshi Kohno](https://homes.cs.washington.edu/~yoshi/)
- [Everyday Cryptography](https://www.isg.rhul.ac.uk/~martin/everydaycryptography.html) by [Keith Martin](https://www.isg.rhul.ac.uk/~martin/)
- [Serious Cryptography](https://nostarch.com/seriouscrypto) by [Jean-Philippe Aumasson](https://www.aumasson.jp/)
- [Crypto Dictionary](https://www.crypto-dictionary.com/) by [Jean-Philippe Aumasson](https://www.aumasson.jp/)
- [Understanding Cryptography](https://www.crypto-textbook.com/) by [Christof Paar](https://www.crypto-textbook.com/christof_paar.php) and [Jan Pelzl](https://www.crypto-textbook.com/jan_pelzl.php)
- [The Joy of Cryptography](https://joyofcryptography.com/) by [Mike Rosulek](https://web.engr.oregonstate.edu/~rosulekm/)
- [Introduction to Modern Cryptography](https://www.cs.umd.edu/~jkatz/imc.html) by [Jonathan Katz](http://www.cs.umd.edu/~jkatz) and [Yehuda Lindell](http://www.cs.biu.ac.il/~lindell/)
- [A Graduate Course in Applied Cryptography](https://toc.cryptobook.us/) by [Dan Boneh](https://crypto.stanford.edu/~dabo) and [Victor Shoup](https://shoup.net/)

## AEADs
### Commitment
#### Papers
- [Authenticated Encryption with Key Identification](https://eprint.iacr.org/2022/1680)
- [On Committing Authenticated-Encryption](https://eprint.iacr.org/2022/1260)
- [Efficient Schemes for Committing Authenticated Encryption](https://eprint.iacr.org/2022/268)
- [How to Abuse and Fix Authenticated Encryption Without Key Commitment](https://www.usenix.org/conference/usenixsecurity22/presentation/albertini)
- [Partitioning Oracle Attacks](https://www.usenix.org/conference/usenixsecurity21/presentation/len)
- [Key Committing AEADs](https://eprint.iacr.org/2020/1153)
- [Fast Message Franking: From Invisible Salamanders to Encryptment](https://eprint.iacr.org/2019/016)
- [Message Franking via Committing Authenticated Encryption](https://eprint.iacr.org/2017/664)
- [Security of Symmetric Primitives under Incorrect Usage of Keys](https://eprint.iacr.org/2017/288)

#### Q&A
- [Do I need a key committing AEAD to be random key robust?](https://old.reddit.com/r/crypto/comments/opm10n/do_i_need_a_key_committing_aead_to_be_random_key/)
- [Understanding the impact of partitioning oracle attacks on stream ciphers](https://crypto.stackexchange.com/questions/88716/understanding-the-impact-of-partitioning-oracle-attacks-on-stream-ciphers)
- [Understanding the impact of partitioning oracle attacks on production deployments of ChaCha/Salsa](https://old.reddit.com/r/crypto/comments/m0gc2z/understanding_the_impact_of_partitioning_oracle/)
- [My breakdown on Partition Oracle Attacks](https://old.reddit.com/r/crypto/comments/n17k3t/my_breakdown_on_partition_oracle_attacks/)
- [Encrypting h(k) for defeating partition oracle attacks](https://crypto.stackexchange.com/questions/88745/encrypting-hk-for-defeating-partition-oracle-attacks)
- [Do CCM and EAX provide key commitment?](https://crypto.stackexchange.com/questions/87779/do-ccm-and-eax-provide-key-commitment)
- [Encrypt-then-HMAC with a single key is secure?](https://crypto.stackexchange.com/questions/88736/encrypt-then-hmac-with-a-single-key-is-secure)
- [Streaming Interface for authenticated encryption?](https://github.com/LoupVaillant/Monocypher/issues/218)

#### Blogs
- [Pa(dding|rtitioning) oracles, and another hot take on PAKEs](https://emilymstark.com/2021/02/01/padding-partitioning-oracles-and-another-hot-take-on-pakes.html)
- [Designing New Cryptography for Non-Standard Threat Models](https://soatok.blog/2020/09/09/designing-new-cryptography-for-non-standard-threat-models/)
- [Why I have settled on XChaCha20+Blake3 as the AE suite of choice for my projects](https://mccarty.io/chacha20-blake3/)
- [Threema: Three Strikes, You’re Out](https://soatok.blog/2021/11/05/threema-three-strikes-youre-out/#invisible-salamanders-with-group-messaging)
- [When a KEM is not enough](https://neilmadden.blog/2021/02/16/when-a-kem-is-not-enough/)
- [Lucid Multi-Key Deputies Require Commitment](https://scottarc.blog/2022/10/17/lucid-multi-key-deputies-require-commitment/)
- [libsodium Robustness](https://doc.libsodium.org/secret-key_cryptography/aead#robustness)
- [Improved client-side encryption: Explicit KeyIds and key commitment](https://aws.amazon.com/blogs/security/improved-client-side-encryption-explicit-keyids-and-key-commitment/)

#### IETF
- [Encrypt-then-MAC for Committing AEAD (cAEAD)](https://github.com/samuel-lucas6/draft-lucas-generalised-committing-aead)
- [The AEGIS family of authenticated encryption algorithms](https://datatracker.ietf.org/doc/html/draft-irtf-cfrg-aegis-aead-00#name-introduction-2)
- [Properties of AEAD algorithms](https://www.ietf.org/archive/id/draft-bozhko-cfrg-aead-properties-00.html#name-key-commitment)
- [The OPAQUE Asymmetric PAKE](https://datatracker.ietf.org/doc/html/draft-irtf-cfrg-opaque-06#section-10.3)
- [[Cfrg] Potential vulnerabilities with OPAQUE](https://mailarchive.ietf.org/arch/msg/cfrg/2W9LoeeiRzAiTWVnDsyxvjYPPmo/)
