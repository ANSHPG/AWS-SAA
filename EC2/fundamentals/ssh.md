## ![Tux, the Linux mascot](/images/shell.svg) Connect from Shell
 

- Download SSH key
  > *pem for >=Win10/ Linux/ Mac* <br>
  > *putty for <Win10*


### Snippet for Connection
```python
ssh
ssh -i your_pem_key.perm ec2-user@public_ip 
```
### Example
``` python

hello@ANSHP MINGW64 ~/Downloads (main)
$ ssh -i \ec2_train.pem ec2-user@ec2_public-ip
   ,     #_
   ~\_  ####_        Amazon Linux 2023
  ~~  \_#####\
  ~~     \###|
  ~~       \#/ ___   https://aws.amazon.com/linux/amazon-linux-2023
   ~~       V~' '->
    ~~~         /
      ~~._.   _/
         _/ _/
       _/m/'
[ec2-user@ip-private-ip ~]$ ^C
[ec2-user@ip-private-ip ~]$
logout
Connection to ec2_public-ip closed.

```


>[!Note]
>Ensure The Security Group for Instanse has Inbound access to *port 22* and your Ip <br>
>*Ctrl + D* to exit
