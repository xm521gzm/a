# 三种工作模式

## （1）本地复制

将本地目录 /var/rsync-src/ 下的文件同步至本地目录 /var/rsync-dest/

```
rsync -r /var/rsync-src/ /var/rsync-dest/
```

## （2）将本地数据同步到远程（push）

将本地目录 /var/rsync-src/ 下的文件同步至远程主机 10.101.11.11 目录 /var/rsync-dest/

```
rsync -r /var/rsync-src/ username@10.101.11.11:/var/rsync-dest/ 
```

## （3）将远程数据同步到本地（pull）

将远程主机 10.101.11.11 目录 /var/rsync-dest/ 下的文件同步至本地目录 /var/rsync-dest/

```
rsync -r username@10.101.11.11:/var/rsync-dest/ /var/rsync-dest/
```