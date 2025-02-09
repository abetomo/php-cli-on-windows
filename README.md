# php-cli-on-windows

```console
PS > php env.php
bool(false)
```

```console
PS > $Env:DEBUG = "yes"
PS > php env.php
string(3) "yes"
```

```console
PS > .\run.bat
D:\a\php-cli-on-windows\php-cli-on-windows>set DEBUG=yes
D:\a\php-cli-on-windows\php-cli-on-windows>php env.php
string(3) "yes"
```
