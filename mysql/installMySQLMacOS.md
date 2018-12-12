## Install MySQL 5.7 on macOS

### Install Homebrew
* Installing Homebrew is effortless, open Terminal and enter :  
 `$  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### Install MySQL
At this time of writing, Homebrew has MySQL version **8** as default, but as we're aiming to get **5.7**, we'll need to append `@5.7` to the default package key:

* Enter the following command : `$ brew info mysql@5.7`  
* Expected output: **mysql@5.7: stable 5.7.22 (bottled) [keg-only]**

To install MySQL enter : `$ brew install mysql@5.7`
