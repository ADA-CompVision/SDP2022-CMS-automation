
## Administration Script

* Lock and unlock during the contests: `ansible-playbook lock_unlock_user_screen.yml --tags lock/unlock`

* Open browser on user side: `ansible-playbook open_browser.yml --tags browser`

* Check syntax in ansible: `ansible-playbook lock_unlock_user_screen.yml --syntax-check`

* Run any sh script: `sh open_browser.sh` or `./open_browser.sh`
 
*Also, you need to perform "xhost +" to allow remote hosts start GUI applications (like browser or screen locker) on contestant machines. Running this command from console will permit it only for the current session: for the permanent access, add this command to /etc/profile.*



