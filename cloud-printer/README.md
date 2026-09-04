# 互维云+远程打印助手（cloud-printer）

一个针对 CUPS 开发的云打印系统，让你的老旧打印机也能支持微信小程序云打印。

## 快速开始

- 微信搜索「互维云+」即可找到小程序
- Docker 内含专属云 ID，小程序扫码即可添加设备
- 支持 x86 与 ARM 架构

## 管理页面（将 ip 换成你的设备 IP）

- `http://ip:8088` — 设备管理页面，可查看设备 ID 等信息
- `http://ip:631` — CUPS 页面，用户名 `root`，密码 `admin123`
- `http://ip:8080` — cups-web 页面，用户名 / 密码均为 `admin`

## 功能

- 基于 CUPS 的远程打印服务，支持微信小程序远程发起打印
- 全文档格式转换：PDF / Word / Excel / PPT / 图片
- USB 与局域网打印机自动发现
- HPLIP 专有插件支持（HP M1136 MFP 等）
- 管理页面内置设备绑定、打印机管理、打印队列监控

## 安装（飞牛 FnDepot 应用源）

1. 在飞牛 FnDepot 客户端中添加应用源：`https://github.com/tzi-shue/FnDepot`
2. 搜索「互维云+远程打印助手」并安装
3. 安装后直接访问 `http://<NAS IP>:8088` 打开设备管理页面（CUPS 管理页默认密码 `admin123`）
4. 安装完成后访问 `http://<NAS IP>:8088` 打开设备管理页面

## 镜像

- `ghcr.io/tzi-shue/cloud-printer:latest`

## 反馈

- 问题反馈：https://github.com/tzi-shue/cloud-printer/issues
- 项目主页：https://github.com/tzi-shue/cloud-printer
