serverspec memo
==============

[serverspec](http://serverspec.org) を試したメモです。

このように実行すればリモートホストで sudo するパスワードを聞いて下さいます。

```
ASK_SUDO_PASSWORD=1 bundle exec rake spec
```
