# DNS

## Unsorted Command Collection
```
hostname --all-ip-addresse
```

```
systemd-resolve --status   #alternative: resolvectl
vim /etc/systemd/resolved.conf
systemctl restart systemd-resolved.service
# alternative
systemd-resolve --interface <iface> --set-dns <dns ip> --set-domain <yourdomain.local>
```

```
dig <>
dig @<server> <>
```

