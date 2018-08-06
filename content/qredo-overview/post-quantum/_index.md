+++
title = "Post-Quantum Cryptography"
description = ""
# Type of content, set "slide" to display it fullscreen with reveal.js
type=""
# Creator's Display name
creatordisplayname = "Qredo Community"
# Creator's Email
creatoremail = "community@qredo.org"
# LastModifier's Display name
lastmodifierdisplayname = "Qredo Community"
# LastModifier's Email
lastmodifieremail = "community@qredo.org"
alwaysopen = true
weight = 1
+++
Qredo uses a suite of post-quantum secure algorithms. Post-quantum cryptography (sometimes referred to as quantum-proof, quantum-safe or quantum-resistant) refers to cryptographic algorithms (usually public-key algorithms) that are thought to be secure against an attack by a quantum computer. Our rational is to be future proof against the intoduction of a quantum computer. In the instance where post-quantum algorithms are not employed, these will be called out expressly as being not post-quantum secure.

### Ring Signatures

A ring signature is a type of digital signature that can be performed by any member of a group of users that each have keys. Therefore, a message signed with a ring signature is endorsed by someone in a particular group of people. One of the security properties of a ring signature is that it should be computationally infeasible to determine which of the group members' keys was used to produce the signature. Ring signatures are similar to group signatures but differ in two key ways: first, there is no way to revoke the anonymity of an individual signature, and second, any group of users can be used as a group without additional setup.

#### Threshold Ring Signature

Unlike standard "t-out-of-n" threshold signature, where t of n users should collaborate to decrypt a message, this variant of a ring signature requires t users to cooperate in the signing protocol. Namely, $t$ parties $(i_1, i_2, ..., i_t)$ can compute a $(t, n)$ ring signature, $σ$, on a message, $m$, on input $(m, Si_1, Si_2, ..., Si_t, P_1, ..., P_n)$.

#### One-Time Linkable Ring Signature

### SIKE

SIKE is a family of post-quantum key encapsulation mechanisms based on the Supersingular Isogeny Diffie-Hellman (SIDH) key exchange protocol. The algorithms use arithmetic operations on elliptic curves defined over finite fields and compute maps, so-called isogenies, between such curves.

### Undeniable Blind Signature Scheme
