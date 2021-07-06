# PortaCode
A template for a lightweight CD/CI server stack

This code sets up a CD/CI server stack which includes
- Private IPFS
- Docker
- Gogs
- BuildBot
- and more to come.

The aim is to produce a distributed, lightweight dev server which will go on anything from an RPi3B+ to a powerful VM or Bare Metal.

# RPi Recommendations
- RPi 3B+
- 16GB microSD for the OS
- USB attached drive of at least 64GiB for Docker persistence which includes the IPFS store which holds configs and the git repo.

This project assumes Debian as the host Linux distro.
