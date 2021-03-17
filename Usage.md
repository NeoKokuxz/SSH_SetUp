# SSH

## Generate SSH on local machine  
```bash
ssh-keygen
```
>This will generate 2 files one is ssh and ssh.pub (Note: Use the key from .pub 

## Add SSH key to github
- Under Github account setting
- SSH and GPG keys
- Add key using the key from .pub file

## Eval the SSH agent 
```bash
eval `ssh-agent`
```
> Please note have to use back-tick `` 

## Add the SSH key to agent
```bash
ssh-add {/Location/keyFile}
```
> This time use the real one not the .pub file

## Done
> Git Clone + SSH_Link
