# 中文学术主页模板

主页：https://sjrgckym.github.io/

使用传统学术个人主页的结构：顶部个人信息与照片、方括号文字导航、个人简介、研究方向与招生、新闻、代表性论文、教学、学术服务。全部论文和学生各有独立页面。界面为中文，未提供的个人资料明确标注为“待填写”，没有虚构研究经历或论文。

## 文件

- index.html：主页，样式已内嵌，编辑此文件即可修改文案和布局。
- publications.html：全部论文。
- students.html：学生页面。
- .nojekyll：空文件，用于跳过 Jekyll 构建。

无第三方依赖，无需安装或构建。下载后双击 index.html 即可查看。

## 修改

1. 将顶部 sjrGCkym 和“待填写”替换为真实的姓名、单位、职务、邮箱、简介及其他资料。
2. 照片位置：替换 index.html 的 portrait 占位块为 img；照片也可以使用 data URL 内嵌，以便单文件发布。
3. 用真实论文替换论文占位条目，将 PDF、代码等占位文字改成实际链接。
4. 同步更新 publications.html 和 students.html。无需某栏目时，可删除对应正文和导航链接。
5. 三个页面都包含相同的 style 样式块；修改公共样式时，请同步修改各页。

## GitHub Pages

本仓库现有发布来源为 **master / (root)**。将文件上传到仓库根目录并提交到 master，GitHub Pages 会自动发布。

新仓库可以使用 main / (root)，仓库名应匹配拥有者的用户名，例如 sjrgckym.github.io。

页面结构参考：https://www.cs.sjtu.edu.cn/~jinhaiming/

[GitHub Pages 官方发布设置](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
