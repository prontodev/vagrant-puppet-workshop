Vagrant + Puppet Workshop
=

Prerequisite: VirtualBox

Installing Vagrant
-

Go to the download page: http://downloads.vagrantup.com/

Get Started with Vagrant
-

Create our first Box

```
$ vagrant init precise32 http://files.vagrantup.com/precise32.box
$ vagrant up
```

The above two commands will create a box named 'precise32' on 
our machine and automatically download a box from the given URL.

After that, we can SSH into the virtual machine with `vagrant ssh`. 
When you are done playing, use `vagrant destroy` to remove it.

We can download the box file in advance, so the first command will be 

```
$ vagrant init precise32 precise32.box
````

Initialize a new Vagrant project directory.

```
$ mkdir ~/Vagrant
$ cd ~/Vagrant
$ vagrant init
```



