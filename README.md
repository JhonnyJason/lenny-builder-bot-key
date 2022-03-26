# Lennys' Developer key for Package signing

## To Import in pacman

```sh
# pacman-key --add builderkey.pub
```

Check Key ID with
```sh
# pacman-key --list-keys
```

Key ID is: F48F6D5F582D3A42AE2DD66B116F7AC9167C9F22

```sh
# pacman-key --lsign-key F48F6D5F582D3A42AE2DD66B116F7AC9167C9F22
```

Also set the trust-level of the key

```sh
# pacman-key --edit-key F48F6D5F582D3A42AE2DD66B116F7AC9167C9F22
```

Then type `trust` choose trustlevel `4` is okay ;-)
Then type `save`

Cheers!
