 # When git gc hangs
 
 Today when running a ```git fetch```, git decided to auto pack the repository, which hang up.
 This is what helped:
 
 ```
 $ git config --global gc.auto 0
 ```
 
 ```git gc``` deletes objects that are no longer part of any branch. To disable this behavior permanently run the command above.
 
 Official documentation for git gc can be found [here](https://git-scm.com/docs/git-gc)
 
 Do not forget to run ```git gc``` occasionally!
