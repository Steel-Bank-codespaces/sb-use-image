# sb-use-image

This uses a customized Docker image at https://hub.docker.com/r/jkitchin/pycse-ddm.

I had to use an 8-core machine so there was enough disk space. It looks like this uses quite a bit of disk space out of the box, maybe more than 36 GB.

```
(base) jovyan@codespaces-dc996c:/workspaces/sb-use-image$ df -h
Filesystem      Size  Used Avail Use% Mounted on
overlay          63G   26G   34G  44% /
tmpfs            64M     0   64M   0% /dev
tmpfs           7.9G     0  7.9G   0% /sys/fs/cgroup
shm              64M     0   64M   0% /dev/shm
/dev/sda1        63G   53M   60G   1% /tmp
/dev/sdb1        29G   11G   19G  36% /vscode
/dev/loop0       63G   26G   34G  44% /workspaces
tmpfs           7.9G     0  7.9G   0% /proc/acpi
tmpfs           7.9G     0  7.9G   0% /proc/scsi
tmpfs           7.9G     0  7.9G   0% /sys/firmware
```

It is pretty fully featured though, and has a complete LaTeX installation and Jupyter Lab installation.

The first time you open the codespace is somewhat slow, maybe 5 minutes?
