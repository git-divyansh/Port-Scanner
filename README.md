# Port-Scanner
A port scanner is a crucial tool in the realm of network security and administration. It serves the purpose of systematically checking the open ports 
on a computer or network to identify potential vulnerabilities or services running on those ports. 

# How To Use
Lets open a CMD or Terminal, and enter commands.
```sh
$ git clone https://github.com/git-divyansh/Port-Scanner.git
$ cd Port-Scanner
$ python3 port-scanner.py
```
Enter IP adress or localhost.

And enter desired port ranges. (example would be 1-30)

After shows all open ports.
# Output
```sh
Please enter IP adress (or localhost): 192.168.1.1
192.168.1.1 is a IP address to scan
Please enter the range of ports in format: (example would be 10-30)
Enter desired port range: 10-30
Port 23 is OPEN on 192.168.1.1.
Port 80 is OPEN on 192.168.1.1.
```
