From within PowerShell run these commands, one at a time.

npm i -g tfx-cli

. $PROFILE

tfx extension create --manifest-globs vss-extension.json

tfx build tasks create 

#fill out the info

tfx build tasks upload --task-path .

#you might have to login to your instance of Azure DevOps 
