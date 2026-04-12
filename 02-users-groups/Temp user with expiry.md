## Temporary User Setup with Expiry

```bash
sudo useradd -m -e 2026-12-31 user-name
```

```bash
sudo usermod -e 2026-12-31 user-name
```

```bash
cat /etc/passwd
```

```bash
sudo su user-name
```

```bash
chage -l user-name
```

```bash
passwd -S user-name
```

