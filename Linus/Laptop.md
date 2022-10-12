# Ignore lid closed on laptop

To ignore the laptop being close edit the below to allow for system to still run when lid is closed. 

```bash
// Edit the following file
sudo nano /etc/systemd/logind.conf

// Uncomment this line 
#HandleLidSwitch=suspend

// Change to
#HandleLidSwitch=ignore

// Restart service with the following
sudo systemctl restart systemd-logind
``` 



