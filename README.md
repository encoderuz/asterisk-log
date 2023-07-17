# asterisk-log

## First of all change configuration into ```/etc/asterist/manager.conf```

```
[general]
enabled = yes  #Turns on AMI
bindaddr = 127.0.0.1 #Only allows localhost connections
port = 5038 #port

[admin] #username
secret=root #password
read=all #Allows all actions
write=all #Allows all actions

```

#### Authentification

```
Action: Login
Username: admin
Secret: root
```

#### Ping

```
Action: Ping
```

#### Info

**SIP: Session Initiation Protocol**
