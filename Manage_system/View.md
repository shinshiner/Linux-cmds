### View the disk
* 查看磁盘剩余空间 `df -hl`
* 查看某目录大小 `sudo du -sh [target path]`

### View the CPU & memory state

* 查看cpu及内存占用信息
```
sudo apt-get install htop
htop
```
* 查看某进程cpu及内存占用信息
```
htop -p [pid]
```

### View the GPU state

* if you are using nvidia graphics card :
  1) install the nvidia driver
  2) run `nvidia-smi`
