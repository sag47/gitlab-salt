gitlab-local
############

This is an attempt at a complete vagrant install from scratch, which should
work on any server that salt can provision.

Getting Started
===============

#. Install `Vagrant <http://www.vagrantup.com/>`_

#. Install salty-vagrant

    ::

        vagrant plugin install vagrant-salt

#. Add the Ubuntu 12.04 base box

    ::

        vagrant box add precise64 http://files.vagrantup.com/precise64.box

#. Fire it up!

    ::

        vagrant up

PLEASE NOTE!!!
==============

This salt state works best with salt 0.17.0 or higher.
