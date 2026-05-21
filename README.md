# OpenStack Neutron 网络组件部署项目
## 项目介绍
基于 CentOS 7 完成 OpenStack Neutron 网络组件部署，实现控制节点 + 计算节点的网络服务配置，掌握 Linux 网桥、网络环境、安全组、元数据代理等核心配置。

## 技术栈
- 操作系统：CentOS 7
- 云平台：OpenStack
- 核心组件：Neutron、Nova、Linux Bridge
- 网络：扁平网络、安全组、DHCP 代理、元数据代理

## 完成内容
1. 节点网络环境配置（混杂模式、br_netfilter 模块）
2. 控制节点 Neutron 安装与数据库初始化
3. ML2 插件、Linux 网桥、DHCP、元数据代理配置
4. 计算节点 Neutron LinuxBridge 代理配置
5. 服务启动、状态验证、端口检测

## 目录说明
- pdf/：部署文档
- config/：核心配置文件
- screenshot/：服务验证截图
- commands.txt：完整部署命令合集

## 验证结果
- 9696 端口正常监听
- Neutron 服务全部启动
- openstack network agent list 状态 UP
 
