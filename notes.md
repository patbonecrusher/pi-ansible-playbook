# PI initial setup

When starting up a PI, you need to ssh into it and do some user level stuff before setting up the ssh keys.

```shell
#install 
brew install esolitos/ipa/sshpass
ansible -i "raspberrypi.local," all -m setup -u pi --ask-pass

```
