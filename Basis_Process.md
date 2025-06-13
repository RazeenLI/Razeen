# Basis Process

1. 查看进程是否存在

```shell
ps -p PID
ps -p PID -o pid,ppid,etime,cmd

```

2. 查看子进程

```shell
pstree -p PID
```

3. 查看gpu
   
```shell
nvidia-smi
```
