**Step 1:** Run this command to create a directory to mount the CD-ROM:

sudo mkdir /mnt/cdrom
 
Step 2: Run this command to mount the CD-ROM:

sudo mount /dev/cdrom /mnt/cdrom or sudo mount /dev/sr0 /mnt/cdrom
 
Step 3: Run this command to find the exact name:

ls /mnt/cdrom
 
Step 4: Run this command to extract the contents of the VMware Tools bundle:

tar xzvf /mnt/cdrom/VMwareTools-x.x.x-xxxx.tar.gz -C /tmp/

Step 5: Run this command to change directories into the VMware Tools distribution:

cd /tmp/vmware-tools-distrib/
 
Step 6: Run this command to install VMware Tools:

sudo ./vmware-install.pl
 
**Step 7:** Run this command to reboot the virtual machine after the installation completes:

sudo reboot
