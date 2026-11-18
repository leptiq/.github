<p align="center"><img src="https://raw.githubusercontent.com/leptiq/.github/refs/heads/main/profile/leptiq-mark.svg" alt="Leptiq" width="96"></p>

# Leptiq

Leptiq is an open-source server for the official Proton apps, written in Rust. It implements the API those apps use, so they can run against a server you host instead of Proton's. Client data stays end-to-end encrypted.

Apps are supported one at a time, each as a separate product. The first is Leptiq Pass, for the Proton Pass clients.

## Repositories

- [core](https://github.com/leptiq/core): the server, with the shared platform and the product crates.
- Each official client that needs changes to connect to a Leptiq server gets its own repository.

Leptiq is not affiliated with or endorsed by Proton AG. "Proton" is a trademark of Proton AG.
