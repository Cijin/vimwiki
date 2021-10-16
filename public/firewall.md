# Setting up firewall:
 1. We will be using **ufw** (Uncomplicated Firewall)
 2. First **allow ssh**, otherwise you will not be able to ssh in :D. Run `sudo ufw allow ssh`
 3. Then, enable firewall; `sudo ufw enable ssh`
 4. To enable other *services* use -> `sudo ufw enable service` or `sudo ufw enable port`
 5. Listing Rules: `sudo ufw status` or `sudo ufw status numbered`
 6. **Deleting Rules**: `sudo ufw delete [rule number]` ex: `sudo ufw delete 2`
 7. To *delete by rules*: `sudo ufw delete [rule name]` ex: `sudo ufw delete allow delete allow http`

