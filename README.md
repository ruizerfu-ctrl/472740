# Git 与 Node.js 练习项目

这是用于复现 Git 入门操作的最小 Node.js 示例。由于未能读取原视频字幕，示例代码与依赖不保证与视频一致。

## 运行

在本文件夹打开终端：

    npm install
    npm start

运行后会输出“Node.js 项目已成功运行！”。

## 文件说明

- index.js：示例程序，可以修改文字练习版本提交。
- package.json：项目说明、运行命令与依赖声明。
- package-lock.json：锁定依赖版本，提交到 Git。
- node_modules/：npm 实际安装的依赖，仅留在本机。
- .gitignore：忽略依赖、环境配置和临时文件。

## Git 操作

    git status
    git diff
    git add index.js
    git commit -m "Update example message"
    git log --oneline

用下面的命令验证依赖目录被忽略：

    git check-ignore node_modules/chalk/package.json

## 远端仓库

https://github.com/ruizerfu-ctrl/472740
