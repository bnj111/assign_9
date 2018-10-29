# assign_9

Which honeypots you deployed? 
I had one honeypot called mhn-honeypot-1

Any issues you encountered? 
There was quite a few issues with the installation process. It had an error that returned repository not found. The way around it was that you had to go inside scripts/install_hpfeeds.sh and arrow down until you found pip install -e git+http://github.com/HurricaneLabs/pyev.git#egg=pyev". Change “HurricaneLabs” to “couozu”. Save it. Go back to “mhn" directory and Run sudo ./install.sh. I also had issues accessing the website because I had to add tcp:80 to firewall settings to mhn-allow-admin

A summary of the data collected: 
The top attacker country was america. The top attacked port was 8088 with 21 number of attacks.

Any unresolves issues:
The attack number kept going down
