# php-cli-on-windows

```console
PS > php env.php
bool(false)
bool(false)
bool(false)
```

```console
PS > $Env:DEBUG = "yes"
PS > $Env:PASSWORD = "xxx"
PS > php env.php
string(3) "yes"
bool(false)
string(3) "xxx"
```

```console
PS > .\run.bat
D:\a\php-cli-on-windows\php-cli-on-windows>set DEBUG=yes
D:\a\php-cli-on-windows\php-cli-on-windows>set USER=test
D:\a\php-cli-on-windows\php-cli-on-windows>php env.php
string(3) "yes"
string(4) "test"
bool(false)
```
