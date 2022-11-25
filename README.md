# Linux
Importnat Command 

Kill all Process with matching Pattern
```bash
pkill -9 -f my_pattern

```
Check all Process with matching Pattern
```bash
ps aux | grep my-pattern

```

SCP (secure copy)

```bash

FROM LOCAL TO REMOTE
scp file.txt remote_username@10.10.0.2:/remote/directory/newfilename.txt

FROM REMOTE TO LOCAL

scp remote_username@10.10.0.2:/remote/file.txt /local/directory

To copy a directory from a local to remote system, use the -r option:

scp -r /local/directory remote_username@10.10.0.2:/remote/directory

```
Copy the all file from directory execpt folder name n current directory


```bash
cp -RT path/folder/ .

```
Copy the all file from directory with folder name in current directory

```bash
cp -r path/folder/ .

```

To check disk space and also check file which are more than 1 GB
```bash
df -H
sudo du -ht 1G /
```
To check Local IP
```bash
hostname -I
ifconfig -a

```


