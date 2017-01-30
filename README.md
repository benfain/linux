# linux
Various Linux-related scripts and commands

```
## create group
groupadd -g gid

## create user and assign to group
useradd -u uid -g gid -G groupname -c "comment" -d /home/user user

## remove user expiry date
chage -I -1 -m 0 -M 99999 -E -1 user
```
