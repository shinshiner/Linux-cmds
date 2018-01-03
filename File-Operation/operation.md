### 改变当前所在目录

* Common usage 
```
cd [target path]
```
* 返回上一级 
```
cd ..
```

### 删除文件

* 删除文件 
```
rm [filename]
```
* 删除文件夹 
```
rm -r [foldername]
```
* 强行删除文件 
```
rm -rf [filename]
```
* 强行删除文件夹
```
rm -rf [foldername]
```

### 上传文件(夹)到服务器

* 传文件 
```
scp -P [port number] [file path in PC] [username@ip address:file path in server]
```
* 传文件夹
```
scp -r -P [port number] [file path in PC] [username@ip address:file path in server]
```

### 从服务器上下载文件(夹)

* 下载文件 
```
scp -P [port number] [username@ip address:file path in server] [file path in PC]
```
* 下载文件夹 
```
scp -r -P [port number] [username@ip address:file path in server] [file path in PC]
```

### 从网络上下载文件(夹)

* 下载单个文件
1) Common usage
```
wget [url address]
```
2) 若文件下载地址含有单个`/`，应指定文件名下载：
```
wget -O [file name] [url address]
```
3) 限速下载
```
wget --limit-rate=[limit rate] [url address]
```
