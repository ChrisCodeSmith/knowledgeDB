# NFS
---
## Server

### Files
`/etc/exports`


### Command Collection
```
exportfs -rrv
```
---
## Client

### Command Collection
```
rpcinfo -p <host>
showmount -e <host>
```