# autossh
Auto Login SSH Server (expect-based)

# Install

```
$ git clone https://github.com/wufeifei/autossh.git
$ sudo cp autossh/autossh /usr/local/bin/
```

# Config

```
$ cat ~/.autosshrc
sername|192.168.1.110|root|password|port
wufeifei|wufeifei.com|root|password|22
```

# Usage

```
$ autossh
############################################################
#                     [AUTO SSH]                           #
#                                                          #
#                                                          #
# [1] 192.168.1.110:feei                                   #
# [2] 10.11.2.103:root                                     #
# [3] 103.21.140.84:root                                   #
#                                                          #
#                                                          #
############################################################
Server Number:(Input Server Num)
```

OR

```
$ autossh 1
```
