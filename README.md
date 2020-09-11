# packer-ubuntu

*Based on [chef/bento](https://github.com/chef/bento)*

Ubuntu base image for virtualbox. 

```
cd packer/ubuntu
packer build -only=virtualbox-iso ubuntu-20.04-desktop-amd64.json
```

```
cd packer/ubuntu
packer build -only=virtualbox-iso ubuntu-20.04-amd64.json
```

