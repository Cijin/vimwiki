# Setting up a digitalocean server
  ## Setting up server:
    1. SSH into root
    2. Creating user: `adduser username`
    3. Adding user to sudo group `usermod -aG sudo username`
    4. To switch to new user `su username`
    5. It is recommended to add your public ssh to the new user, which would allow you to do something like this `ssh username@ip`

