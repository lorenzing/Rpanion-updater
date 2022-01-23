# Rpanion-updater
Rpanion-server update script
Find all the documentation on Rpanion-server here: https://github.com/stephendade/Rpanion-server

#Install rpanion-updater
Connect to RaspberryPi via SSH client
Download and install rpanion-updater script
```
# cd /etc/init.d
# sudo wget https://raw.githubusercontent.com/lorenzing/Rpanion-updater/main/rpanion-updater
# sudo chmod +x /etc/init.d/rpanion-updater
```

- Reboot the RaspberryPi
```
# sudo reboot
```

# Use the rpanion-updater

## Update the server script:
This command is very useful, allowing you to download the newest release of Rpanion-server via internet
```
# sudo /etc/init.d/rpanion-updater
```
