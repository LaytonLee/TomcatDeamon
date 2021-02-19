# TomcatDeamon

## 脚本功能 

脚本主要实现了以下两个功能：
1. 监控tomcat的运行状态，在tomcat进程down掉后自动启动tomcat
2. 在tomcat资源占用过高时记录jvm的状态，便于后续的分析

## 注意事项

下载脚本后，在本地运行时需要修改脚本中的一下语句为本地对应文件路径：

```bash
tomcatStartCmd=/Users/layton/Developer.localized/Environment/apache-tomcat-9.0.34/bin/startup.sh
```