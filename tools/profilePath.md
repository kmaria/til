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
