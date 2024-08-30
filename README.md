## Automator自动化工具运行方式
- 方式1
  - 下载后用命令执行`automator path/xxx.workflow`
- 方式2
  - 下载后双击打开，点击Automatic的运行按钮
- 方式3
  - 下载后双击打开，文件->转换为->类型选择应用程序->保存成应用程序类型，之后可以双击应用程序直接运行

## 自动化工具列表
### **上传Github图库** [download](https://github.com/wdzawdh/AutomaticRepo/releases/download/UploadImage.workflow-release/UploadImage.workflow.zip)
* 此工具会将选择的图片上传你的Github，将链接转换为jsDelivr CDN链接，并返回Markdown格式的图片格式
* 工具会自动提示配置你的GithubApiToken，仓库地址，分支名，目标文件夹路径 [创建Token](https://github.com/settings/tokens)

### **自动上传截图** [download](https://github.com/wdzawdh/AutomaticRepo/releases/download/UploadScreenshot.workflow-release/UploadScreenshot.workflow.zip)
* 此工具会打开截图，将截图上传你的Github，将链接转换为jsDelivr CDN链接，并返回Markdown格式的图片格式
* 工具会自动提示配置你的GithubApiToken，仓库地址，分支名，目标文件夹路径 [创建Token](https://github.com/settings/tokens)
> 注意：使用前需要添加权限，系统设置->隐私与安全性->录屏->添加此工具

### **TinyPng压缩图片** [download](https://github.com/wdzawdh/AutomaticRepo/releases/download/TinyImage.workflow-release/TinyImage.workflow.zip)
* 此工具会将选择的图片使用TinyPng压缩
* 默认大于150k的图片才会进行压缩，修改配置可以用Automator打开workflow在“过滤Finder项目”中修改
* 工具会自动提示输入你的TinyPngApiKey [查看ApiKey](https://tinify.com/dashboard/api)

### **TinyPng批量压缩图片** [download](https://github.com/wdzawdh/AutomaticRepo/releases/download/TinyImages.workflow-release/TinyImages.workflow.zip)
* 此工具会将你选择的文件夹中的图片批量使用TinyPng压缩
* 默认大于150k的图片才会进行压缩，修改配置可以用Automator打开workflow在“过滤Finder项目”中修改
* 工具会自动提示输入你的TinyPngApiKey [查看ApiKey](https://tinify.com/dashboard/api)
> 注意：免费TinyPng账户每月限制500张图片 [查看余量](https://tinify.com/dashboard/api)

### **修改图片尺寸** [download](https://github.com/wdzawdh/AutomaticRepo/releases/download/ResizeImage.workflow-release/ResizeImage.workflow.zip)
* 此工具会将选择的图片进行尺寸修改，等比例放大或缩小

### **随机桌面壁纸** [download](https://github.com/wdzawdh/AutomaticRepo/releases/download/RandomWallpaper.workflow-release/RandomWallpaper.workflow.zip)
* 此工具会获取Bing每日图片，随机一张设置为桌面壁纸

### **收集项目图片** [download](https://github.com/wdzawdh/AutomaticRepo/releases/download/CollectImages.workflow-release/CollectImages.workflow.zip)
* 此工具会将选择的项目文件夹中的所有图片提取出来
