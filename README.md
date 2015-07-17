# bin
my scripts.

## Howto
Clone in your home directory.

```
cd ~
git clone git@github.com:chkkchy/bin.git
```

Create a command in this directory and Symlink it to your `usr/local/bin`.

```
ln -sfn $HOME/bin/{command} /usr/local/bin/{command}
```
