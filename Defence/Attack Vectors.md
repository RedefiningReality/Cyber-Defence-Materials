# Common Attack Vectors
[John's Red Team Manual](https://docs.google.com/document/d/1MVC5l0cuEw2p5pXNvvb1kXyee-IxitJW7X_eibU_4B0/)

## FTP
- outdated service
- anonymous login
- plaintext login and data transfers
- insecure passwords

## SSH
- outdated service
- insecure passwords

## SMB
- outdated service
- anonymous login
- outdated encryption
- insecure passwords

## HTTP
- outdated service
- web attacks (SQLi, FIV, FUV, XSS, CSRF, etc.)

**Note:** There are so many, that as a defender, you'll just have to accept that you won't be able to find them all. Set up good monitoring or a Web Application Firewall (WAF).

## HTTPS
- same as HTTP
- outdated encryption

## Privilege Escalation
https://gtfobins.github.io/
- outdated distro
- outdated service
- bad sudo permissions
- bad file permissions (wrong ownership or rwx on file)
- SUID/SGID binaries
- SUID/SGID capability set on binary (check `getcap`)