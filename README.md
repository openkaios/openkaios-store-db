# openKaiOS Store - DB

这里是 openKaiOS 商店的数据库仓库，这里是基于 bHacker 的非官方商店。

## 如何上架应用到商店

要添加您的 app，您需要创建一个描述它的文件。该文件的名称应为 `[app id].yml` 并位于 `apps` 文件夹中。

App id 是应用程序的域反转，例如：`app.example.com` 将是 `com.example.app`

您可以下载 `example/app.template.yml` 模板并填写对应的值，可以参考其他 app。

为了存储/服务您的开源应用程序，我们推荐 GitHub 或 Gitee release 处获取。

## 滥用

如果您看到一个应用程序

- 窃取您的数据
- 包含恶意软件
- 或者对您的设备有破坏性行为...

请在 issue  中报告该应用程序，我们将对其进行调查。

## 客户端

### KaiOS / GerdaROM devices
- https://github.com/openkaios/openkaios-store-client

### Desktop Website
 （暂无）

## Backend
本商店的基本构成均基于以下项目：

 - DB & DB Generator: [https://gitlab.com/banana-hackers/store-db](https://gitlab.com/banana-hackers/store-db)
 - Client: [https://github.com/strukturart/bHacker-store-client](https://github.com/strukturart/bHacker-store-client)
 - Web: [https://github.com/jkelol111/webstore](https://github.com/jkelol111/webstore)
 - Rating Server: [https://gitlab.com/banana-hackers/simple-ratings-server](https://gitlab.com/banana-hackers/simple-ratings-server)
