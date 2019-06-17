## Oxygen OS Gps.conf Back China GPS回国模块
This module is aimed at solving the deviation problem of OxygenOS by replacing gps.conf

I didn’t realize its necessity until I nearly drove to river by using positioning service.

It may be or not effective to other mobile devices but what I’m sure is it has nothing to do with causing unable to boot.

Q: How to check if the GPS positioning service has deviation? My GPS positioning service is accurate as I see.

This issue is concerning the positioning principle, which means there’s deviation when converting into coordinates. In this condition, you can ask your friend share the position. So when you use positioning service yourself, there’re some many other factors such as Base stations, WI-FI, signals, Aiding positioning which help accurate positioning. You can know only when you and your friend are apart for a certain long distance.

此模块针对一加氧OS在国内定位偏移导致的问题，其原理就是替换gps.conf



曾经我也没想过替换这个，但是，前几天差点把我导航开到河里了，我觉得这个还是非常有必要的。

其他手机也许能用，也许没用，反正不影响你开机。不会导致开不了机的问题。


问：如何测试GPS定位有偏移？我自己打开手机定位是准的呀？


答：这个涉及定位原理，就是转化坐标的时候出现了偏差，所以需要你朋友发定位，假如你自己发定位，还有基站呀，wifi呀，信号呀，辅助定位所以一般准确的，即使不准确也偏差不大，而你朋友的位置就只是坐标偏差较远了，才能知道是否有偏差。


## Feedback
* [问题反馈Git Repository](https://github.com/Magisk-Modules-Repo/Oxygen-OS-Gps.conf-Back-china/issues/new)


## Update Log 更新日志
##v1.0.3 更改ID符合magisk要求

#v1.0.3 changed the ID to correspond to the norms of the magisk.

##V1.0.1 增加说明和反馈和英文解释

#V1.0.1 added description, feedbacks and English explanation

##V1.0.0 初始版本

#V1.0.0 original version
