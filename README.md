<p align="center">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github.com/FiloSottile/age/blob/main/logo/logo_white.svg">
        <source media="(prefers-color-scheme: light)" srcset="https://github.com/FiloSottile/age/blob/main/logo/logo.svg">
        <img alt="The age logo, an wireframe of St. Peters dome in Rome, with the text: age, file encryption" width="600" src="https://github.com/FiloSottile/age/blob/main/logo/logo.svg">
    </picture>
</p>

# Awesome age [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A collection of projects and resources in the age file encryption ecosystem.

* [Implementations](#implementations)
* [Plugins](#plugins)
* [GUIs](#guis)
* [Tools](#tools)
* [Integrations](#integrations)
* [Articles](#articles)
* [Development](#development)

For more, explore [the *age-encryption* GitHub topic](https://github.com/topics/age-encryption)!

⭐️ Featured or official — 🧪 Beta or experimental

## Implementations

* ⭐️ [age](https://filippo.io/age) ([Go docs](https://pkg.go.dev/filippo.io/age), [man page](https://filippo.io/age/age.1)) — CLI and Go reference implementation.

* ⭐️ [rage](https://str4d.xyz/rage) — Rust implementation, fully interoperable and feature complete.

* [pyrage](https://github.com/woodruffw/pyrage) — Python bindings for rage.

* 🧪 [kage](https://github.com/android-password-store/kage) — Work-in-progress implementation for Kotlin/JVM and Android.

* 🧪 [AgeKit](https://github.com/jamesog/AgeKit) — Work-in-progress Swift implementation on top of CryptoKit.

* 🧪 [wage](https://github.com/str4d/wage) — Wasm package powered by rage.

* [rage-wasm](https://github.com/kanru/rage-wasm) — Wasm wrapper of rage.

* [agemobile](https://github.com/MarinX/agemobile) — gomobile support for age.

## Plugins

* ⭐️ [age-plugin-yubikey](https://github.com/str4d/age-plugin-yubikey) — YubiKey (and other PIV tokens) plugin.

* [age-plugin-se](https://github.com/remko/age-plugin-se) — Apple Secure Enclave plugin, supporting native keys.

* 🧪 [age-plugin-tpm](https://github.com/Foxboron/age-plugin-tpm) — TPM 2.0 plugin.

* [age-plugin-trezor](https://github.com/romanz/trezor-agent/blob/master/doc/README-age.md) — Trezor hardware wallet plugin, supporting native keys.

* 🧪 [age-plugin-sntrup761x25519](https://github.com/keisentraut/age-plugin-sntrup761x25519) — Post-quantum hybrid plugin mixing NTRU Prime and X25519.

* 🧪 [age-plugin-fido](https://github.com/riastradh/age-plugin-fido) — Prototype of a symmetric encryption plugin for FIDO2 keys.

## GUIs

* ⭐️ [Winage](https://winage.spiegl.dev/) — Contextual menu driven Windows GUI.

* [agewasm](https://github.com/MarinX/agewasm) ([live](https://age-wasm.ey.r.appspot.com/)) — Static HTML and Wasm in-browser encryption tool.

* 🧪 [rage-encry.pt](https://rage-encry.pt/) — In-browser encryption/decryption tool powered by wage.

## Tools

* ⭐️ [passage](https://github.com/FiloSottile/passage) — Fork of password-store that uses age in place of gpg.

* [PaperAge](https://github.com/matiaskorhonen/paper-age) — Easy and secure paper backups of secrets.

* [pa](https://github.com/biox/pa) — A simple password manager, written in portable POSIX shell.

* [agebox](https://github.com/slok/agebox) — Easy file repository encryption tool, focused on simplicity and gitops.

* 🧪 [kbs2](https://github.com/woodruffw/kbs2) — A secret manager backed by age.

* 🧪 [ciphey](https://www.nickzana.dev/projects/ciphey/) — Password and secret manager.

* [age-keygen-deterministic](https://github.com/keisentraut/age-keygen-deterministic) — Deterministically generate age keys from a passphrase with Argon2id.

* [vanity-age](https://github.com/seaofmars/vanity-age) — Vanity age public key bruteforcer.

## Integrations

* [agenix](https://github.com/ryantm/agenix) — age-encrypted secrets for NixOS.

* [ragenix](https://github.com/yaxitech/ragenix) — Drop-in replacement for agenix in Rust.

* [homeage](https://github.com/jordanisaacs/homeage) — Nix home-manager module for runtime decryption of declarative age files.

* [scalpel](https://github.com/polygon/scalpel) — Secret provisioning to Nix-generated service config files.

* [agenix-rekey](https://github.com/oddlama/agenix-rekey) — agenix extension facilitating automating per-host secret rekeying.

* [age.el](https://github.com/anticomputer/age.el) — age encryption support for Emacs.

* [passage.el](https://github.com/anticomputer/passage.el) — passage support for Emacs.

* ⭐️ [SOPS](https://github.com/mozilla/sops#encrypting-using-age) — Flexible and widely integrated secret manager.

* [kustomize-age](https://github.com/jmhodges/kustomize-age) — Kustomize plugin for using age encrypted files in Secrets.

* [Kustomizer](https://kustomizer.dev/guides/artifacts-encryption/) — Kubernetes configuration as OCI artifacts, natively supports age.

* [chezmoi](https://www.chezmoi.io/user-guide/encryption/age/) — Dotfiles manager with native age support.

* [gopass](https://github.com/gopasspw/gopass/blob/master/docs/backends/age.md) — Password manager with a built-in age backend.

* [Logseq](https://web.archive.org/web/20230422154136/https://twitter.com/logseq/status/1587905208667230209) — Open-source knowledge base, uses age for its cloud Sync.

* [eldim](https://github.com/daknob/eldim) — A file upload proxy that encrypt files with age.

* [paw](https://github.com/lucor/paw) — Cross-platform password manager app.

* [Cryptocam](https://cryptocam.gitlab.io/) — Android app that encrypts video with age as it is recorded.

## Articles

* [age and Authenticathed Encryption](https://words.filippo.io/dispatches/age-authentication/)

* [KEMs and Post-Quantum age](https://words.filippo.io/dispatches/post-quantum-age/)

* [My age+YubiKeys Password Management Solution](https://words.filippo.io/dispatches/passage/)

* Len, Julia, Paul Grubbs, and Thomas Ristenpart. ["Partitioning Oracle Attacks."](https://eprint.iacr.org/2020/1491) *USENIX Security Symposium.* 2021.

* Gailly, Nicolas, Kelsey Melissaris, and Yolan Romailler. ["tlock: Practical Timelock Encryption from Threshold BLS."](https://eprint.iacr.org/2023/189) *Cryptology ePrint Archive.* 2023.

* Stäuble, Mirco. ["Actually Good Encryption? Confusing Users by Changing Nonces."](https://ethz.ch/content/dam/ethz/special-interest/infk/inst-infsec/appliedcrypto/education/theses/project_MircoStauble.pdf) *Semester project. Department of Computer Science, ETH Zürich.* 2022.

* [gitattributes age encrypt](https://seankhliao.com/blog/12020-09-24-gitattributes-age-encrypt/) — Encrypting and decrypting files with gitattributes.

* [age Encryption in Python with pyrage](https://blog.yossarian.net/2022/07/25/age-encryption-in-python-with-pyrage) — Announcement of pyrage with extensive technical details.

## Development

* ⭐️ [age-encryption.org/v1](https://age-encryption.org/v1) — The official file format specification.

* [c2sp.org/CCTV/age](https://c2sp.org/CCTV/age) — Comprehensive implementation-agnostic test suite of over 100 vectors.

* 🧪 C2SP/C2SP#5 — age-plugin spec (draft)
