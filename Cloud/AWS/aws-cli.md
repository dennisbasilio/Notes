# aws-cli

## Installation
``` shell
curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
sudo softwareupdate --install-rosetta
sudo installer -pkg AWSCLIV2.pkg -target /

# To validate
which aws
aws --version
```