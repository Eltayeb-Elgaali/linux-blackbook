```sudo dnf install -y podman```

```podman -v```

```sudo -i```

```podman image ls```

```podman container list```

```podman container list --all```

```mkdir -p /opt/var/lib/mariadb```

```podman run -d --name mariadb -v /opt/var/lib/mariadb/:/var/lib/mysql:Z -e MYSQL_ROOT_PASSWORD=Password1 docker.io/mariadb``` or ```podman container run -d --name mariadb -v /opt...```

```podman -v```

```podman exec -it mariadb /bin/bash```

```mariadb -u root -p```

```ls -l /opt/var/lib/mariadb```

```podman generate systemd --name mariadb```

```!! > /etc/systemd/system/mariadb.service```

```systemctl daemon-reload```

```systemctl enable --now mariadb```

```systemctl stop mariadb```

```podman container ls --all```

