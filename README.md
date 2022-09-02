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

