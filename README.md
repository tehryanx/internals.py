# internals.py

take a list of domains or ips on stdin and return only those that point to private / internal ipv4 or ipv6 addresses. 

```
$ cat domains.txt
www.target.com
shop.target.com
internal.target.com

$ cat domains.txt | internal
internal.target.com
```
