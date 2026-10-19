# AI 超级员工

面向 Windows 的 AI 员工桌面工作空间：招聘员工、配置身份与长期准则，通过聊天安排工作，并按需要分配能力插件与服务账号。

## 下载

[下载最新 Windows 64 位完整包](https://github.com/jixn-hu/ai-employee-releases/releases/latest/download/AIEmployee-Windows-x64.zip) · [查看版本与更新说明](https://github.com/jixn-hu/ai-employee-releases/releases)

1. 下载 **AIEmployee-Windows-x64.zip** 并完整解压。
2. 双击 **AIEmployee.exe** 启动，无需 Node.js 或 npm。
3. 在「模型与设置」配置自己的大模型接口、模型名称和 API 密钥。
4. 按需配置插件，再招聘员工、分配账号与连接。

本仓库提供桌面程序发布包与更新说明。

## 能力

- 多模型切换、员工招聘与资料、简洁聊天、任务分配和多员工协作。
- 插件分类与能力分配，支持网页阅读、AIHOT 资讯、本地文件、SSH、邮箱、图片生成和墨流内容发布。
- PostgreSQL、SQL Server、RabbitMQ、New API 服务连接。
- 长期记忆与准则、定时和事件触发、系统检查员、配置导入导出。
- 账号同步；未登录时使用本地模式。

外部服务需要自行配置可访问的地址与凭据。程序包不附带个人账号、模型密钥或工作数据。

## 更新与数据

在「模型与设置 → 软件更新」检查更新，新版本也会自动提醒。默认来源为本仓库。

升级时关闭旧程序，将新版完整 ZIP 解压到新目录后运行。用户数据保存在 `%APPDATA%\digital-world-desktop`，原有员工、任务和配置继续使用。程序目录中的资源、DLL 和子文件夹需要保留完整。

当前采用下载后手动更新方式。
