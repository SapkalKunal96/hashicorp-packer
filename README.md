download packer binary from packer.io for windows and for linux install packer

clone this repo on your machine and change the vpc & subnet Id's

make sure you have auto assign public IP address are enbaled for subnet else SSH connection will fail

commands to execute

packer.exe validate --var-file packer-vars.json packer.json

packer.exe inspect --var-file packer-vars.json packer.json

packer.exe build --var-file packer-vars.json packer.json
