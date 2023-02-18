# Usage

* If you prefer cloning with HTTPS URLs:

```shell
$ # If you want gpgsign to be enforced:
$ cp ~/.antigen/bundles/rowheel/gitconfig/gitconfig_with_gpgsign_enforced ~/.gitconfig
$ touch ~/.gitignore_global ~/.ssh/allowed_signers

$ # If you don't want gpgsign:
$ cp ~/.antigen/bundles/rowheel/gitconfig/gitconfig_with_gpgsign_disabled ~/.gitconfig
$ touch ~/.gitignore_global
```

* If you prefer cloning with SSH URLs:

```shell
$ # If you want gpgsign to be enforced:
$ cp ~/.antigen/bundles/git@github.com:rowheel/gitconfig/gitconfig_with_gpgsign_enforced ~/.gitconfig
$ touch ~/.gitignore_global ~/.ssh/allowed_signers

$ # If you don't want gpgsign:
$ cp ~/.antigen/bundles/git@github.com:rowheel/gitconfig/gitconfig_with_gpgsign_disabled ~/.gitconfig
$ touch ~/.gitignore_global
```
