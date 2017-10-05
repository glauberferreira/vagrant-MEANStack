# 99xt/MEANStack

[![license](https://img.shields.io/github/license/99xt/vagrant-MEANStack.svg)](https://github.com/99xt/vagrant-MEANStack/blob/master/LICENSE)

99xt/MEANStack is pre-packaged Vagrant box that provides you a solid development enviroment for your MEAN-based apps without installing all those software packages, tools and a web server on your local machine. This intends to provide clean and synced development envorement between each team members and also between multiple computers when you work on the same project.

If something goes wrong, you can simply destroy and re-create it.

## Requirements

* Download and install [Vagrant](https://www.vagrantup.com)
* Download and install [VirtualBox](https://www.virtualbox.org/)

## Usage

```
mkdir <app-dir>
cd <app-dir>
vagrant init 99xt/MEANStack
vagrant up --provider virtualbox
```

See the Vagrant Docs [here](https://www.vagrantup.com/docs/)
