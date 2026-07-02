GitHub Pages 上传说明

请把本文件夹 github-pages-upload 里的内容上传到 GitHub 仓库根目录。

需要上传的内容：
1. index.html
2. assets 文件夹
3. .nojekyll 文件

上传后开启 GitHub Pages：
1. 进入 GitHub 仓库。
2. 点击 Settings。
3. 点击 Pages。
4. Source 选择 Deploy from a branch。
5. Branch 选择 main，目录选择 /root。
6. 点击 Save。
7. 等待 1 到 3 分钟，GitHub 会生成访问链接。

生成的链接通常是：
https://你的用户名.github.io/仓库名/

说明：
index.html 是首页文件，assets 里包含封面、背景音乐和所有视频资源。
.nojekyll 用于避免 GitHub Pages 处理静态资源时出现路径问题。
