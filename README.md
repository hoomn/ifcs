# rt-fr
Real-time face recognition system（基于实时视频流的人脸识别系统）

# 原理
#### 1、实时视频流处理模块
                
+ 架构设计

[![](https://res.infoq.com/articles/video-stream-analytics-opencv/en/resources/figure1.png)](https://www.infoq.com/articles/video-stream-analytics-opencv "实时视频流架构设计")
+ [英文参考链接](https://www.infoq.com/articles/video-stream-analytics-opencv)
+ [中文参考链接](https://infoq.cn/article/video-stream-analytics-opencv)


#### 2、去重模块

由于，检测对象可能长时间处在视频监控范围之内，因此，该时间段的视频帧充斥着大量重复检测对象。对所有重复对象都去做后续的1：N人脸识别显然不合理，因此需要合理的去重设计。


#### 3、人脸识别模块
+ 系统架构
+ windows环境配置
    + 列表二-1
    + 列表二-2
    + 列表二-3
+ 列表三
    * 列表一
    * 列表二
    * 列表三
    
    
# 环境配置
+ linux
    + [Zookeeper配置](https://github.com)
    + [Kafka配置](https://github.com)
    + [Hadoop配置](https://github.com)
+ windows
    + [Zookeeper配置](https://www.jianshu.com/p/f7037105db46)
    + [Kafka配置](https://www.jianshu.com/p/64d25dcf8300)
    + Hadoop配置：
      * [下载Haddop](http://hadoop.apache.org/releases.html)
      * 修改hadoop-x.x.x/etc/hadoop/hadoop-env.cmd中的JAVA_HOME (路径不能空格)