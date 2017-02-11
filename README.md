# Getting Started with OpenStack 
A little project to quickly set up all-in-one OpenStack using Vagrant

## Introduction
The following will deploy a Virtual Machine on your laptop that will enable you to
follow along step by step during the session.

## Preparation:

These instructions should download a CentOS7 Vagrant Box, Install RDO and provide
you an environment to follow along with in the original [Getting Started With
OpenStack](https://www.openstack.org/videos/austin-2016/getting-started-with-openstack)
video. These are the same (updated) materials used to present that session.


1. Install Vagrant: 
```https://www.vagrantup.com/docs/installation/
```

2. Download the Vagrantfile: https://radez.fedorapeople.org/Vagrantfile:

3. Start the virtual maching and install OpenStack

```$ vagrant up
```

   Wait for the install to complete, it will take some time.

## Pausing the Installation

To suspend your installation you can use:
```$ vagrant halt
```

To resume it:
```$ vagrant up
```

## Troubleshooting.

If you have trouble, please file a issue or pull request and we'll help you
out as quickly as possible.

If your vagrant environment fails for any reason, you can start off with
a clean slate by destroying the VM:

```$vagrant destroy -f
```

Then beginning the process again with `vagrant up`.

## Acknowledgments

Thanks to Dan Radez for the initial content, and to both him and
Kenneth Hui for the introductory presentation at the Austin OpenStack 
Summit.
