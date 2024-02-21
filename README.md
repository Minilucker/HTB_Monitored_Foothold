# HTB Monitored

## SPOILER AHEAD



_________________________________________________________________________________



this script covers almost the entirety of the foothold part for htb monitored,
however it does not cover the admin api key obtention.
once you have the correct api key :

```bash
python3 -W ignore exploit.py --help
usage: foothold script for Monitored from htb season 4 [-h] [-u USERNAME] [-p PASSWORD] [-li IP] [-lp PORT] [-akey APIKEY]

it gives you a shell (if you have a correct admin api key) on the machine

options:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        the username of the acc to create, default : minilucker
  -p PASSWORD, --password PASSWORD
                        the password of the acc to create, default : password
  -li IP, --ip IP       the ip of your listener
  -lp PORT, --port PORT
                        the port of your listener
  -akey APIKEY, --apikey APIKEY
                        the admin apikey, needed for admin account creation
```

