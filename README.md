# ClaudiaMIND
IRC hivemind DDoS tool

Requires socks.
```sudo apt-get install python-socksipy```
or
```sudo pip install PySocks```

# Getting the program & updating
* Getting the program: ```git clone https://github.com/ClaudiaDAnon/ClaudiaMIND.git```
* Updating the program: Make sure you're in the ClaudiaMIND directory, then ```git pull```

# Usage

```$ python claudiamind.py```

Port: 9050 for the ```service tor``` and 9150 for the Tor browser (and therefore works on Windows)

Simply: If you're running Windows, start the Tor browser and type 9150 into the port column. If you're running linux, download tor if not installed (```sudo apt-get install tor```), make sure the service is running (```sudo service tor start```) and either enter 9050 or nothing (9050 is default).
**Alternatively, you can use the Tor browser port (9150) on Linux too.**
*Protip: On Linux, you can run both the Tor browser and the service.*

# Reporting policy
The script compares your IP to the Tor IP to make sure you're using Tor, and then sends me or any OP who requested it your **TOR IP**, only for statistical purposes and easier bugfixing. **Again, don't worry, that is not your real IP address.**.

It also sends me the version of your script, so I can tell some people to update it, etc.
