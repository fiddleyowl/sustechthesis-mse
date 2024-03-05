# 南方科技大学材料科学与工程系本科学位论文模板 sustechthesis-mse

[![Actions Status](https://github.com/fiddleyowl/sustechthesis-mse/actions/workflows/compile.yaml/badge.svg)](https://github.com/fiddleyowl/sustechthesis-mse/actions/workflows/compile.yaml)
[![GitHub downloads](https://img.shields.io/github/downloads/fiddleyowl/sustechthesis-mse/total)](https://github.com/fiddleyowl/sustechthesis-mse/releases)
[![Download Analysis](https://img.shields.io/badge/Download-Analysis-blue.svg)](https://qii404.me/github-release-statistics/?repo=/fiddleyowl/sustechthesis-mse/)
[![GitHub commits](https://img.shields.io/github/commits-since/fiddleyowl/sustechthesis-mse/latest)](https://github.com/fiddleyowl/sustechthesis-mse/commits/master)
[![GitHub release](https://img.shields.io/github/v/release/fiddleyowl/sustechthesis-mse?&label=%E5%8F%91%E5%B8%83%E7%89%88)](https://github.com/fiddleyowl/sustechthesis-mse/releases/latest)

Southern University of Science and Technology Thesis Template LaTeX Template for bachelor's degree.

本项目是南方科技大学材料科学与工程系本科学位论文模板，基于 [sustechthesis](https://github.com/iydon/sustechthesis) 项目修改，在此感谢原作者的贡献。

## 下载

* 发布版：[GitHub Release](https://github.com/fiddleyowl/sustechthesis-mse/releases/latest)
* 开发版：直接 Git clone，或者点击绿色 `Code` 下载ZIP压缩包。此版本不保证稳定性，提供给有经验的 TeX 用户使用。

## 模板使用

请阅读 [main.pdf 文档](https://github.com/fiddleyowl/sustechthesis-mse/releases/latest)。

## 文档架构

* `config/preamble.tex`: 导言区，导入宏包，宏定义。
* `config/info.tex`: 论文信息，例如：标题，作者，等。
* `main.tex`: 主文档，编排章节顺序。
* `slides.tex`: beamer 幻灯片模版。


## XeLaTeX 构建
- 使用 Makefile: `make`, `make clean` ......
- 或，使用 `latexmk`
    - 构建: `latexmk main`
    - 清理: `latexmk -c main`

## 使用Overleaf在线编辑

* 下载源码zip压缩包
* 登录Overleaf，点击`New Project`，选中`Upload Project`
* 上传源码zip压缩包
* 点击左上角的`Menu`，将设置中的编译器由`pdfLaTeX`改为`XeLaTeX`

## 更新日志

每个版本的详细更新日志，请见 [CHANGELOG.md](CHANGELOG.md)。

## 正式版本发布流程

1. 手动更新 CHANGELOG.md
2. 手动更新 sustechthesis.cls 中定义的版本号 `\version`
3. 使用 git 命令行工具，打 tag 并推送到远端仓库


```git
#标记本地tag
git tag v1.2.0
#推送本地tag到远程
git push origin v1.2.0

#删除本地tag
git tag -d v1.2.0
#删除远程tag
git push --delete origin v1.2.0
```

## 致谢

* 本模版根据南方科技大学-教学工作部发布的相关 [《撰写规范》和《样例》](http://tao.sustech.edu.cn/studentService/graduation_project.html) 编写，如有冲突以官网规定为准。
  * 如果《样例》中存在与《撰写规范》中的规定不符之处，以《撰写规范》中的文字叙述为准。
* 本模板基于材料科学与工程系示例文档修改格式，格式要求可能因指导老师、年份等因素而有所不同。
