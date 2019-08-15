# SSH

## Generating a new SSH key and adding it to the ssh-agent
https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

## Checking for existing SSH keys

To list the files in the .ssh directory, if they exist
```
ls -al ~/.ssh
```

## Access the SSH public key

This copies the contents of the id_rsa.pub file to your clipboard
```
pbcopy < ~/.ssh/id_rsa.pub
```
