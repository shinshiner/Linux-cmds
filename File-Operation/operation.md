### 删除
* 删除文件 `rm filename`
* 删除文件夹 `rm -r foldername`
* 强行删除文件 `rm -rf filename`
* 强行删除文件夹 `rm -rf foldername`

### 上传文件(夹)到服务器
* 传文件 `scp -P port_number file_path_in_PC username@ip_address:file_path_in_server`
* 传文件夹 `scp -r -P port_number file_path_in_PC username@ip_address:file_path_in_server`

### 从服务器上下载文件(夹)
* 下载文件 `scp -P port_number username@ip_address:file_path_in_server file_path_in_PC`
* 下载文件夹 `scp -r -P port_number username@ip_address:file_path_in_server file_path_in_PC`
