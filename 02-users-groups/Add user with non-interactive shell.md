## Add user with non interactive shell

```bash
ssh user@server-name
```
```bash
sudo useradd -m -s /usr/sbin/nologin user-name
```
```bash
cat /etc/passwd
```
```bash
sudo su user-name
```
```bash
grep nologin /etc/passwd
```
```bash
id user-name
```
```bash
sudo userdel -r user-name
```
