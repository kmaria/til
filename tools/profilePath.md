## ZSH allows you to use special mapping of environment variables

So you can simply do:

```
# append
path+=('/home/path/to/bin')
# or prepend
path=('/home/path/to/bin' $path)
# export to sub-processes (make it inherited by child processes)
export PATH
```


The order files are read is:

```
/etc/zshenv    # Read for every shell
~/.zshenv      # Read for every shell except ones started with -f
/etc/zprofile  # Global config for login shells, read before zshrc
~/.zprofile    # User config for login shells
/etc/zshrc     # Global config for interactive shells
~/.zshrc       # User config for interactive shells
/etc/zlogin    # Global config for login shells, read after zshrc
~/.zlogin      # User config for login shells
~/.zlogout     # User config for login shells, read upon logout
/etc/zlogout   # Global config for login shells, read after user logout file
```
