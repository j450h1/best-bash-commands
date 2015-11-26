# best-bash-commands
This is a Jupyter notebook with useful bash commands. 


LAMuP Ubuntu

#ssh in

ssh -i "KEY_NAME.pem" ubuntu@52.26.63.167

#Change permissions to permissive for folder

sudo chmod 777 /folderlocation

#Copy file to remote
scp -i 'KEY_NAME.pem' filename.html ubuntu@52.26.63.167:/var/www/html

#Copy folder to remote
scp -r -i 'KEY_NAME.pem' static ubuntu@52.26.63.167:/var/www/html
