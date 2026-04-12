## Create user - add user to newly created group - has user admin rights - inspect

```bash
useradd dev-user
```
```bash
cat /etc/passwd
```
```bash
vim /etc/passwd
```
```bash
apt install vim
```
```bash
passwd dev-user
```
```bash
cat /etc/shadow
```
```bash
su - dev-user
```
```bash
whoami
```
```bash
rm -rf /sbin
```
```bash
groupadd developers
```
```bash
cat /etc/group
```
```bash
usermod -aG developers dev-user
```
