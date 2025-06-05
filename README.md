# mipa-client-install

This script is used to manually set up a FreeIPA client on an openSUSE system.

It performs tasks such as:
- Adding the client host to the FreeIPA server
- Retrieving the Kerberos keytab
- Installing required authentication packages
- Configuring `sssd`, `krb5`, and `nsswitch.conf`
- Setting up certificate authority trust

**Note:** Almost all of it was based on the excellent instructions from https://gist.github.com/Aethylred/1a5f0eb685ce8e50b2823cda13690e7c

Ensure the script is run as root, and that the IPA server is reachable via SSH.
