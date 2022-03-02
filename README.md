# certauth

Simple script for creating and signing self-signed certificates.

It has no dependencies other than `openssl` and a POSIX compatible shell.

Usage:

Edit the `CA_*` options in the script to change things such as the name.

Initialize a CA:
```certauth init```

Create a certificate and a private key signed by your CA:
```certauth create <name>```

Wipe your CA:
```certauth clean```
