## Install MySQL on macOS

### Install MySQL

`$ brew install mysql`

### Homebrew

Install **brew services** first : `$ brew tap homebrew/services`

Load and start the MySQL service : `$ brew services start mysql`    


### MySQL
Open Terminal and execute the following command:
 `brew services start mysql`
 
To set the root password:  
 `mysqladmin -u root password 'yourpassword'`  

You may need to login as the root user:
 `mysql -u root -p`


