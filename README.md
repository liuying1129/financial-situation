# 配置github项目的在线访问网址

## 前置条件

1、仓库必须是公开的（Public）

2、必有index.html且位置正确：请确保该文件位于仓库的根目录，或者你打算指定的/docs文件夹中

## 配置步骤

1、进入仓库设置：打开仓库主页，点击顶部的 "Settings"（设置）选项卡。

2、找到Pages选项：在左侧边栏中，向下滚动找到并点击 "Pages"。

3、在 "Build and deployment" 部分，将 "Source" 的下拉菜单设置为 "Deploy from a branch"（从分支部署）。

4、在 "Branch" 部分，选择要发布的分支（如main）。

5、在旁边的文件夹下拉菜单中，选择 "/ (root)"（如果你的 index.html 在根目录）。

6、保存并等待：点击 "Save"（保存）按钮。GitHub 会立即开始部署，通常需要 1-2 分钟。

## 访问网址

配置成功后，你的网页将通过以下格式的网址访问：

https://<你的GitHub用户名>.github.io/<仓库名>/index.html 或

https://<你的GitHub用户名>.github.io/<仓库名>

小提示：因为入口文件是 index.html，所以网址末尾会自动指向它，你无需在URL中额外添加 /index.html。
