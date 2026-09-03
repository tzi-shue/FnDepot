# 互维云+远程打印助手（cloud-printer）

把一台普通的飞牛 NAS / Linux 机器（工控机、树莓派、龙芯等）变成「云打印机」的飞牛 fnOS 应用。

## 功能

- 基于 CUPS 的远程打印服务，支持微信小程序远程发起打印
- 全文档格式转换：PDF / Word / Excel / PPT / 图片
- USB 与局域网打印机自动发现
- HPLIP 专有插件支持（HP M1136 MFP 等）
- 管理页面内置设备绑定、打印机管理、打印队列监控

## 安装

1. 在飞牛 FnDepot 客户端中添加应用源：`https://github.com/tzi-shue/FnDepot`
2. 搜索「互维云+远程打印助手」并安装
3. 安装时设置 CUPS 管理员密码（默认 `admin123`，建议修改）
4. 安装完成后访问 `http://<NAS IP>:8088` 打开管理页面，`http://<NAS IP>:631` 为 CUPS 管理界面

## 镜像

- `ghcr.io/tzi-shue/cloud-printer:latest`

## 反馈

- 问题反馈：https://github.com/tzi-shue/cloud-printer/issues
- 项目主页：https://github.com/tzi-shue/cloud-printer
