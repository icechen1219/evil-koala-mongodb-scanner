# 邪恶考拉mongodb空口令扫描器

本软件仅供对客户已授权的系统使用！

依赖库：pymongo

使用方式：python mongodb-scanner.py -h ip -p port -m 100

-h 必须输入参数，支持ip(192.168.1.1)，ip段（192.168.1），ip范围指定（192.168.1.1-192.168.5.100）,ip列表文件（ip.txt）。

-p 可选参数，指定要扫描的端口，未指定即使用27017端口扫描

-m 可选参数，指定线程数量，默认200

默认扫描结果保存在 result.txt中

使用示例：

python mongodb-scanner.py -h ip.txt

python mongodb-scanner.py -h 10.34

python mongodb-scanner.py -h 192.168.10

python mongodb-scanner.py -h 192.168.1.5 -p 27017 -m 100


