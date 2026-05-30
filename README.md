## Hi there 👋

I'm a college student in India, building things close to the metal — systems programming, network security, cryptography, and low-level C/C++.

---

## projects
 
### 🔐 [hermes-messenger](https://github.com/karlson1337/hermes-messenger)
End-to-end encrypted terminal messenger for \*nix, written in C/C++.
- X25519 + XSalsa20-Poly1305 encryption via libsodium (`crypto_box_seal`) — server forwards ciphertext it can't read
- Ed25519 identity keypairs; private keys stored locally, encrypted with Argon2-derived keys
- SQLCipher-encrypted local chat history
- TCP socket server with pthreads for concurrent connections
### 🐚 [shellfish](https://github.com/karlson1337/shellfish)
Lightweight Unix shell written in C++17.
- Pipelines (`|`), I/O redirection (`>`, `>>`, `<`), environment variable expansion
- Persistent history via GNU readline (`~/.shellfish_history`)
- Directory stack (`cd -`), script execution mode, clean `SIGINT` handling
---
 
## interests
- Systems & OS internals
- Network programming (sockets, protocols)
- Cryptography & security
- Low-level C/C++
---
 
> *Building things that matter from the ground up.*
