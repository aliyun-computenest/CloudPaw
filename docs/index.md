![image.png](cloudpaw.png)
# CloudPaw 服务简介

CloudPaw 是一款基于 [CoPaw](https://copaw.agentscope.io/) 开发的阿里云 AI 助手，帮助个人开发者利用阿里云资源进行开发与运维工作。部署在你自己的环境中：
    阿里云资源管理 — 通过自然语言对话管理 ECS、OSS、RDS 等阿里云资源，简化日常开发与运维操作。
    能力由 Skills 决定，有无限可能 — 内置阿里云 CLI 操作、资源编排等。更多阿里云 Skills 正在持续接入中，敬请期待！
    数据全在本地 — 不依赖第三方托管。


## 部署流程


1. 访问计算巢 CloudPaw [部署链接](https://computenest.console.aliyun.com/service/instance/create/cn-hangzhou?spm=5176.24779694.0.0.48ab4d22uORwmU&type=user&ServiceId=service-ea1d139a460a4a9ea649)，直接点击**下一步：确认订单**：  
    ![image.png](1.png)

2. 在订单确认页，核对实例费用，预计花费 0.178元/小时（请以实际为准），点击 **立即创建** 开始自动部署。
    ![image.png](2.png)

3. 部署完成后获取访问地址：  
    ![image.png](3.png)  

4. 访问服务，输入第3步中获取的用户名和密码，阅读并同意使用协议后，点击**登录**：
    ![image.png](4.png)

5. 配置百炼API_KEY（[获取百炼API_KEY](https://bailian.console.aliyun.com/cn-beijing/?tab=globalset#/efm/api_key)）(也可选择其他模型服务，请按需配置):
    ![image.png](5.png)

6. 配置模型（请按需选择合适的模型）：
    ![image.png](6.png)

7. 请使用阿里云编排Agent（默认）进行对话：
    ![image.png](7.png)

## 使用指南

可以尝试以下的 query 让 CloudPaw 帮你实现哦～

> 我想快速搭建一个私有网盘服务，能够通过网页访问、上传下载文件、管理用户权限，并支持基本的文档在线预览功能。我希望整个部署过程尽量简化，不需要手动配置服务器环境、安装依赖或调试Web服务，而是通过一种自动化的方式完成应用的初始化和基础设置。部署完成后，我希望能直接通过浏览器访问网盘首页，使用默认管理员账号登录并开始使用，同时确保数据存储具备基本的持久性，不会因服务重启而丢失。

> 我叫 StackWalker，帮我创建一个个人主页并上线到云端。我希望页面包含：个人介绍、技能、项目经历、联系方式。风格尽量简洁清爽，适配手机和电脑。

> 我叫 StackWalker，帮我把一个 API 服务快速发布到云端。我希望默认提供 /health 和 /hello 两个接口，并给我可直接调用的地址和示例请求，配置尽量简单清晰。

## 问题反馈

遇到软件的Bug，可通过以下方式联系我们。
    ![image.png](8.png)


## 常见问题
### 如何配置百炼其他模型
设置>模型>添加模型，输入模型ID后点击创建：

![image.png](9.png)

