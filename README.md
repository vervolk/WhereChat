# WereChat

WereChat / Волкочат is an email-based chat client: a local, multi-frontend mail client that presents e-mail conversations as chats. It is designed as a pet project and hobby-grade tool, not as a high-security or enterprise messaging solution.

Planned frontends include a console client, TUI client, Windows GUI client, Android client, and a local web client talking to a shared core.

## Status

This is an early-stage wibecode project, built with extensive use of neural networks and AI-assisted coding tools. Expect rough edges, inconsistent code style, and frequent breaking changes.

## Security and cryptography

WereChat’s cryptography is intended as **gate** latch level protection: it helps against casual snooping and honest people accidentally looking where they should not, but it is not designed to resist targeted attacks, state-level adversaries, or professional incident responders.

WereChat is a client-only application and does not provide or depend on any proprietary server or cloud infrastructure. It works on top of existing e-mail infrastructure (SMTP/IMAP/POP and related standards). Optional crypto backends (such as OpenPGP or GOST/Kuznyechik libraries) are not bundled and must be installed separately, where legally permitted.

For full details and important notices, see:

- [DISCLAIMER.md](./DISCLAIMER.md)  
- [DISCLAIMER.ru.md](./DISCLAIMER.ru.md)

## License

WereChat is free software, licensed under the
[GNU General Public License v3.0 (GPLv3)](./LICENSE).

See the `LICENSE` file for the full license text.

## Author

Created and maintained by **vervolk**.
