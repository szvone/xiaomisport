# 小米运动自动刷步数

> 小米运动自动刷步数

## Github Actions 部署指南

### 一、Fork 此仓库

### 二、设置账号密码

添加名为  **SCKEY**、**USER**、**PWD**、**STEP** 的变量，值分别为 **server酱推送key（0关闭）**、 **账号（仅支持手机号）**、**密码**、**步数（0则为1w-2w之间随机）**

> Settings-->Secrets-->New secret

### 三、多账户(用不上请忽略)

多账户请用 **#** 分割 然后保存到变量 **USER** 和 **PWD**

#### 例如

**13800138000#13800138001** 变量 **USER**

**abc123qwe#abcqwe2** 变量 **PWD**

## 注意事项

1. 每天运行一次，在下午 6 点

2. 多账户的数量和密码请一定要对上 不然无法使用!!!
