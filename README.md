# flume-hdfs-sink-king

原作者博客链接：https://www.cnblogs.com/30go/p/9962933.html

项目原始出错：https://gitee.com/pang123/flume-hdfs-sink-king

#### 项目介绍
使用flume1.8的包flume-hdfs-sink源码修改
主要解决滚动文件时，可以按照分钟、小时、天(整点)来生成文件。

打包后的文件在target_jar文件夹中。

#### 使用说明
然后在配置hdfsSink时增加以下配置项

| 配置项 | 说明 |
| -----|---------|
| timeRollerFlag| 默认值：day<br>minutes 每分钟滚动文件<br>hour 每小时滚动文件<br>day 每天0点滚动文件 |




