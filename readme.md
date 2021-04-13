
# Website Blocker in Python

Setting up the Website Blocker on Ubuntu

1. Download the Repository.
2. Check Hosts using the command sudo nano /etc/hosts
3. Run sudo crontab -e and add this line:
    tip: pwd to where you saved the website_blocker.py file and add it after the @reboot python 3 as shown below.
    
    @reboot python3 /home/homefolder/documents/website_blocker.py

4. Exit and then run  

    sudo python3 website_blocker.py
    

