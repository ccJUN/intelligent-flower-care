# intelligent-flower-care
智能花草照料系统


## 第一阶段(20161001)

**预期特性：**

* 检测：温度（已有）、湿度、光照、<del>肥料</del>
* 自动化：浇水（定时定量）
* 移动化：手机检测与操控

**开发板选择：**
* [x] Arduino（搭配 [johnny-five](https://github.com/rwaldron/johnny-five/) 进行 Node.js 开发）
* [ ] 树莓派
* [ ] Webduino
* [ ] Tessel
* [ ] Espruino

**选择纬度**：
* 社区活跃度
* 配件丰富度
* 购买便利性
* 入门&学习成本

**已知工作量：**
* 硬件选择与购买
* 服务器搭建
* 程序实现（网络传输、检测功能、定时功能）
* 移动端 H5 页面

**费用清单：**
* 湿度传感器：￥5.5
* 光照传感器：￥10.9
* WIFI 无线模块：￥16.9
* 蓝牙模块：￥25.5
* 杜邦线：￥14.8
* 迷你面包板：￥15
* Arduino 保护盒：￥6.9
* 502 胶水：￥3.9
* 焊接 I2C 转接板：￥14.8
* USB 转 DC：￥3
*电磁阀 12v  ￥9.5 / 水泵 ￥40(二选一)
*继电器   ￥15


---- 总计：￥141.6 ----

** 1期讨论方案所需工具**

*水泵
https://detail.tmall.com/item.htm?spm=a230r.1.14.6.zuXm1u&id=528846930196&cm_id=140105335569ed55e27b&abbucket=6

*电磁阀
https://item.taobao.com/item.htm?spm=a230r.1.14.20.bDknGD&id=45271613910&ns=1&abbucket=6#detail

*继电池
https://detail.tmall.com/item.htm?spm=a230r.1.14.6.Wyc2YX&id=41539011204&cm_id=140105335569ed55e27b&abbucket=6

*摄像头
https://item.taobao.com/item.htm?spm=a230r.1.14.168.YL6UQD&id=15852059858&ns=1&abbucket=6#detail

** 1期讨论方案所需工作量**

1.浇水模块
2.wifi获取消息和展示
3.水量和湿度的关系
4.光源和温度的关系

** 后续工作量 **
1.多盆栽处理的方式
2.摄像头观察生长情况
3.整个体积的优化


