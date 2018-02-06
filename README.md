Convenience utility for generating magnet URL's for torrent clients, given a hash key.

*Really, this was just an exercise for me to get started writing command line utilities with node / npm. And it happens to be marginally useful.*

Install it:
```
sudo npm install -g magnet-link-generator
```

Use it:
```
maglink thehashkeyicopiedfromsomesite
```
Outputs:
```
magnet:?xt=urn:btih:thehashkeyicopiedfromsomesite
```