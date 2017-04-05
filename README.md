# Vagrant Bootstrap

## Summary

The purpose of this project is to start from generic CentOS 6 and 7 Vagrant boxes and enhance them with the tools needed for development.
Both CentOS 6 and CentOS 7 are included.

## Concept of Operation

You run `./build.sh centos6` in this directory.   It does the following things:

  * Bring-up the vagrant system in the centos6 directory, doing all needed provisioning.
  * This includes logic to add the VBox guest additions for a specific version of VirtualBox
  * It stops the box and exports the package as a vagrant box.

This box can then be imported into the environment and used.
