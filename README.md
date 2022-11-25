join a Ubuntu 20.04 machine to a Windows AD domain
```
vars:
  nameserver1: '192.168.11.91'  # DNS1
  nameserver2: '192.168.11.92'  # DNS2
  user: nix.join                # user for join domain
  passwd: ''			              # password for user
  domain_name: cde.ruru.lan	    # Domain name
  group: acc_srv_nix            # Group in AD for adding sudo rights
```

original article https://lanedirt.tech/2021/11/how-to-join-a-ubuntu-20-04-machine-to-a-windows-ad-domain/
