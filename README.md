
```bash
$ xcode-select --install
$ sudo easy_install pip
$ sudo pip install battleschool
$ battle -K --config-file https://raw.githubusercontent.com/marksb/battle-config/master/config.yml
```

## Special Note about Alfred

According to [this article](http://support.alfredapp.com/kb:symlinked-apps) is
not possible to use `brew cask alfred link` to find installed applications via
`brew cask`

To work around that issue, you should add default's Caskroom directory inside
Alfred's preferences:

```
/opt/homebrew-cask/Caskroom
```
