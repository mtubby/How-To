# Multiple git accounts / ssh keys: 

 

## Clone a new repo with different ssh key 

git -c core.sshCommand="ssh -i private_key_file" clone host:repo.git 

## Set current repo to use different ssh key 

git config  core.sshCommand "ssh -i ~/.ssh/keyname" 

git remote show origin -i "~/.ssh/keyname" 

