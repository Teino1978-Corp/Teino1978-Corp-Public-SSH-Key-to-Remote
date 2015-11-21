Add ssh key to host in two line

```bash
ssh-keygen -t rsa
```
```bash
cat ~/.ssh/id_rsa.pub | ssh user@hostname 'cat >> .ssh/authorized_keys'
```