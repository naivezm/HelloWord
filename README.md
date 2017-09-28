# Cantool Windows APP 项目需求文档

> 小组成员：胡庆庆，张德胜，李耀，王杰

## 图表分析

![用例图](http://om0ttwn6c.bkt.clouddn.com/%E4%BE%8B%E5%9B%BEcantool.png)

## 详细需求分析

- 在 windows 平台下建立可视化的带有 GUI 界面的Windows app , 能够很好的完成展示用户要求的信息

- 在弹出式的 ComBox 中实现以下功能
  - 以下拉列表形式选择本机可用 COM 口
  - 设定相应 COM 口的波特率 115200, 数据位数 8, 停止位数 1 , 保存在设定文件中

- 实现 CAN 装置的速率设置 , 工作状态 (open) 设置 , 初始化状态 (Close) 设置, 保存在设定文件中

- 对接收到的 CAN 信息进行及 CAN 信号数据库进行解析 ,  并将 CAN 信息原始数据进行显示

- 