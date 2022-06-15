# Proxmox BareMetal Provisioning Project

Hello world.

This is the repository for Franklin Lee's Proxmox Automation project.

The goal is getting a debian system from a base configuration and build it to a fully deployed proxmox host. The aim is to get it as close to 100% automated as possible through tools such as the preseed file to answer all the questions in a debian install, ansible playbooks to apply on a complete installation, packer for the appserver machine images and terraform to deploy those images to my proxmox hosts.

In my lab I have three hosts to work with:

Mac Pro 2011

Lenovo TS140

HP ML110 Gen9

I will be doing the preseed method via USB for the Mac Pro. Rest of my hosts will be done via PXE boot.

## TO-DO

- Build USB preseed flow for Mac Pro
- Set-up PXE preseed flow for the TS140 and HP ML110 Gen9
- Build Ansible playbooks for post-install set-up of proxmox