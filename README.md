# Kedge Project

Information regarding project setup, automation and accounts.

- accounts.txt - list and description of all bot accounts that are used by Kedge project


### Working with BlackBox encrypted files

Some files (*.gpg) are GPG encrypted using [BlackBox](https://github.com/StackExchange/blackbox)
To view or work with those files you have have [BlackBox](https://github.com/StackExchange/blackbox) installed.
If you have permissions you can view/edit those files using following BlackBox.
Some usefully [BlackBox](https://github.com/StackExchange/blackbox) commands:


| Name:                               | Description:                                                            |
|-------------------------------------|-------------------------------------------------------------------------|
| `blackbox_cat <file>`               | Decrypt and view the contents of a file                                 |
| `blackbox_edit <file>`              | Decrypt, run $EDITOR, re-encrypt a file                                 |
| `blackbox_edit_start <file>`        | Decrypt a file so it can be updated                                     |
| `blackbox_edit_end <file>`          | Encrypt a file after blackbox_edit_start was used                       |