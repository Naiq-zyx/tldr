# gpg-zip

> Encrypt files and directories in an archive using GPG.
> More information: <https://www.gnupg.org/documentation/manuals/gnupg/gpg_002dzip.html>.

- Encrypt a directory into `archive.gpg` using a passphrase:

`gpg-zip {{[-c|--symmetric]}} {{[-o|--output]}} {{archive.gpg}} {{path/to/directory}}`

- Decrypt `archive.gpg` into a directory of the same name:

`gpg-zip {{[-d|--decrypt]}} {{path/to/archive.gpg}}`

- List the contents of the encrypted `archive.gpg`:

`gpg-zip --list-archive {{path/to/archive.gpg}}`
