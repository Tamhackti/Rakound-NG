:warning: **Use this repo as old Rakound project is no longer being maintained** :warning:

![Rakound-NG](https://github.com/Tamhackti/Rakound-NG/assets/3861998/3d5b6527-f52f-40bc-8a24-0556b743dbde)

# Rakound-NG

Rakound-NG is a tool written in Python. Its main goal is to simplify vizualisation of Bloodhound data. It allows to access insignificant data, such as passwords, stored in Active Directory. The tool is provided with various queries in order to retrieve valuable data.

Moreover, cracked passwords (via JohnTheRipper) and hashes (via Impacket Secretsdump) can be imported to modify abuse paths and perform statistics.

Rakound-NG needs Bloodhound data to perform queries. **It is not packaged to collect data by itself.**

## Requirements

Rakound-NG needs the following requirements to work:

* Neo4j database
* Python3
* Bloodhound data

## Quick setup

From terminal, create python environment and install dependencies :

```bash
$ virtualenv -p python3 env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

Run Rakound-NG :

```bash
$ python3 rakound-ng.py
```

## Full documentation

Full documentation is available here : https://rakound-ng.readthedocs.io/en/latest/
