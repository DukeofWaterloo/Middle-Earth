# Middle-Earth
A collection for all my bash and other management scripts for my Home (Lab) when I'm away from Home.

(Also functions as a centralized cloud backup in the event of a horrible no good very bad solar flare that destroys my network!) 

<br> Here's a quick breakdown of what's what: <br>



**hobbiton:** Personal 2-in-1 laptop used as a daily driver for studying, gaming, and other day to day activities. Runs Fedora 34.Linux as the primary operating system with Windows 10 as a backup OS in the event of windows-only software (such as RekordBox DJ suite).

**moria:** Central hub for both the storage and serving of files across the network. Functions as a hybrid Network Attached Storage through dedicated Samba shares with Plex media server integrated throughout. Also functions as a host for a Minecraft game server (Version 1.1.18) among friends and solves cryptographic hashes to support the security and efficiency of the Ethereum blockchain. Powered by Ubuntu Linux 20.04 LTS for both up-to-date packages combined with long term stability.

**khazad-dum:** Windows 10 machine that works alongside moria to authenticate transactions on the proof of work based Ethereum blockchain.

**numenor:** Legacy 2008 Mac Pro 3,1 machine with Proxmox hypervisor, based on Debian Linux, installed on bare metal. Has done plenty in its many years of life and served me well as the first machine in my home lap. Currently hosts two linux virtual machines, **forostar** and **hyarrostar**.

**forostar:** Debian Linux virtual machine running under numenor that hosts a Minecraft server (Version 1.1.17) for friends to come and plan on. Will likely be merged in some way with the server running on **moria**.

**hyarrostar:** Ubuntu Linux virtual machine run on numenor that primarily serves as a mongoDB server for web development projects but also functions as a remote compile server for C/C++ development. In addition, NGINX software is configured to provide a reverse-proxy into the network and Pi-Hole runs as a DNS sinkhole to stop internet advertisements across computers, phones, and smart-TVs across the network.


