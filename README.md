# garage
Storing all the references, links, useful or waste resources which may or may never be required.

## Domain
Get a free domain name for testing from [freennom](https://www.freenom.com/).

## Linux
- [How To Set Up a Firewall with UFW on Ubuntu](digitalocean.com/community/tutorials/how-to-set-up-a-firewall-with-ufw-on-ubuntu-16-04)

### Commands
- **whereis**: The whereis command in Linux is used to locate the binary, source, and manual page files for a command.
- **ps -aux**: To list all the running process.
- **kill -9 pid**: To kill a process.

### Install nvm on linux
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
OR
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```

## Nginx

- [How To Secure Nginx with Let's Encrypt on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-18-04)
- [How To Install Nginx on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-18-04)
  - Adjusting firewall, Setting Up Server Blocks

## AWS

### Mount Disk to Linux

Use below command to check the attached disk it can be mount/unmounted.
```
sudo lsblk
```

Use the lsblk -f command to get information about all of the devices attached to the instance. 
```
sudo lsblk -f
```

Create a directory to map/mount the disk
```
sudo mkdir /data
```

Use the following command to mount the volume at the directory you created in the previous step. 
```
sudo mount /dev/xvdf /data
```

[Make an Amazon EBS volume available for use on Linux](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-using-volumes.html)

## Ebook Editor

- [Moopato](https://moopato.com/)

## Newsletter Services
- Revue: Unlimited Subscribers for free tier.

## Blogging Websites
- Hashnode
- Medium
- Freecodecamp
