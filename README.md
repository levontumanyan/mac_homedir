```brew list```

ca-certificates
fzf
gettext
gh
libidn2
liblinear
libssh2
libunistring
lua@5.3
nmap
openssl@1.1
pcre
tree
wget
zsh-autosuggestions
fzf
gh
nmap
tree
wget
zsh-autosuggestions

# Brew leaves 
brew list -1 to "Force output to be one entry per line" (see man brew). However, please note that if you want to re-install everything you asked from brew before, it's better to generate your list using brew leaves --installed-on-request (short: brew leaves -r) …so once you install from that list you will get only your tools incl. the dependencies that matter at that moment—v.s. using the output of brew list that will include dependencies that might have become obsolete by the time you wish to re-install your tools. – PDK Nov 19, 2021 at 11:45

```brew leaves --installed-on-request```
fzf
gh
nmap
tree
wget
zsh-autosuggestions

**Note**
This is a note

**Warning**
This is a warning
:zzz:
