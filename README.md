# picrepo

- 获取token
  - 个人设置页面->开发者设置
  - 选择Personal access tokens，选择生成新token，添加描述,并添加选项repo
  - 迅速保存获得的token
- vscode picgo设置
  - 记得下载
  - 打开设置, 过滤出picgo
  - 设置如下:
  - ![screenshot](https://cdn.jsdelivr.net/gh/Doublc-Qluv/picrepo@main/notes/screenshot.png)
    1. current设置为GitHub
    2. Branch选择仓库的分支，默认为master(新建仓库默认main)
    3. custom url 图片上传链接
        - 原版:https://raw.githubusercontent.com/[用户名]/[仓库名]/[分支名]
        - cdn加速:https://cdn.jsdelivr.net/gh/[用户名]/[仓库名]@[分支名]
    4. path是图片存储在仓库中的路径