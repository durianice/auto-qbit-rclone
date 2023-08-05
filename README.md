# auto-qbit-rclone
## Download
```
cd ~ && wget https://raw.githubusercontent.com/CCCOrz/auto-qbit-rclone/main/AutoQbitRclone.sh
chmod a+x AutoQbitRclone.sh
```
## qBittorrent Download Options
√ torrent 完成时运行外部程序
```
bash /root/AutoQbitRclone.sh --path="/media/movies/" "%N" "%F" "%R" "%D" "%C" "%Z" "%I"
```
## Params
- path : rcloneName:/$path/
- %N：Torrent 名称
- %L：分类
- %G：标签（以逗号分隔）
- %F：内容路径（与多文件 torrent 的根目录相同）
- %R：根目录（第一个 torrent 的子目录路径）
- %D：保存路径
- %C：文件数
- %Z：Torrent 大小（字节）
- %T：当前 tracker
- %I: 信息哈希值 v1
- %J：信息哈希值 v2
- %K: Torrent ID

