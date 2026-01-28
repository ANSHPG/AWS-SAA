## ![Tux, the Linux mascot](/images/shell.svg) Connect from Shell
 

- Download SSH key
  > *perm for >=Win10/ Linux/ Mac* <br>
  > *putty for <Win10*
- Ensure The Security Group for Instanse has Inbound access to port 22 and your Ip

### Snippet for Connection
```
ssh
ssh -i your_perm_key.perm ec2-user@public_ip 
```
