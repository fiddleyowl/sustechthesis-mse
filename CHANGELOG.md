# Changelog

此处记载了 sustechthesis 中所有值得留意的改动，格式参照 [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)。

点击版本号即可在 GitHub 上查看相邻版本间的代码变动。

Changelog 维护应保持最新版本在文件上面的原则，日期格式按照 ISO 8601 的标准: `YYYY-MM-DD`.

#### 变更分类：*major*, *minor*, *bug-fix*。

#### *major* release trigger:

- `Changed`：现有功能变更。
- `Removed`：现有功能移除。

#### *minor* release trigger:

- `Added`：引入新功能。
- `Deprecated`：标记即将被删除的功能。

#### *bug-fix* release trigger:

- `Fixed`：错误修复。
- `Security`：安全漏洞修复。

#### 使用提示

- 未发布版本使用形如 "`[Unreleased]`" 作为二级标题，
- 预发布版本使用形如 "`[1.0.2-rc.1] - 2021-06-11`" 作为二级标题，
- 正式发布版本使用形如 "`[1.0.1] - 2020-07-25`" 作为二级标题。

## [Unreleased](https://github.com/fiddleyowl/sustechthesis-mse/compare/v1.3.8-mse...HEAD)

## [1.3.8-mse](https://github.com/fiddleyowl/sustechthesis-mse/compare/v1.3.7-mse...fiddleyowl:sustechthesis-mse:v1.3.8-mse) - 2024-04-30

### Changed
- 调整图注和表注的格式，样例要求居中。

### Fixed
- 修复了目录中摘要章节的跳转问题。
- 修复了可能的脚注分页问题。

## [1.3.7-mse](https://github.com/fiddleyowl/sustechthesis-mse/compare/v1.3.6-mse...fiddleyowl:sustechthesis-mse:v1.3.7-mse) - 2024-03-11

### Added
- 增加了结论章节。
- 增加了样例文档。

### Changed
- 调整标题页样式，清除无副标题或主标题太短时标题与下方内容的间距。
- 调整列表格式，移除多余的空行。
- 调整参考文献格式，移除可能包含的DOI，链接等多余信息。

### Removed
- 移除了幻灯片模板。

## [1.3.6-mse](https://github.com/iydon/sustechthesis/compare/v1.3.6...fiddleyowl:sustechthesis-mse:v1.3.6-mse) - 2024-03-05

根据材料科学与工程系示例文档修改格式。

### Added
- 增加了一些示例文本，如公式、图片等。

### Changed
- 根据样例，调整全文页边距为上下 1 in，左右 1.25 in，取消左侧装订线偏移。
- 调整了全文行间距。
- 摘要中指导老师增加了职称。
- 修改了章节格式，每章节均为新页。
- 修改了目录样式，增加了摘要的页码，并调整了字样和缩进。
- 修改了图注表注的样式，使用一个中文空格分隔图号和图名，表号和表名。
- 调整子图的编号格式，并移至子图的左上角。

## [1.3.6](https://github.com/iydon/sustechthesis/compare/v1.3.5...v1.3.6) - 2024-02-28

### Added
- 增加 Overleaf 编译指引（[#45](https://github.com/iydon/sustechthesis/issues/45)）。
### Changed
- 更新参考文献配置（[#44](https://github.com/iydon/sustechthesis/issues/44)）。

## [1.3.5](https://github.com/iydon/sustechthesis/compare/v1.3.4...v1.3.5) - 2023-05-20

### Fixed
- 修复表格字体为五号（[#42](https://github.com/iydon/sustechthesis/issues/42)）。
- 修复参考文献字体为五号（[#43](https://github.com/iydon/sustechthesis/issues/43)）。

## [1.3.4](https://github.com/iydon/sustechthesis/compare/v1.3.3...v1.3.4) - 2022-05-16

### Changed
- 修改行距，标题，段前缩进，目录标题距离（[#35](https://github.com/iydon/sustechthesis/pull/35), [#36](https://github.com/iydon/sustechthesis/pull/36)）。
- 修改页边距，修改伪粗等级（[#38](https://github.com/iydon/sustechthesis/pull/38)）。
- 添加了三线表与`\ref{}`的样例（[#38](https://github.com/iydon/sustechthesis/pull/38)）。

## [1.3.3](https://github.com/iydon/sustechthesis/compare/v1.3.2...v1.3.3) - 2022-05-16

### Added
- 加入 VScode 项目编译配置。
- 加入 pdf 元数据。
- 摘要和目录加入罗马页码（[#31](https://github.com/iydon/sustechthesis/issues/31)）。

### Fixed
- 修复参考文献、附录、致谢的链接跳转位置错误（[#32](https://github.com/iydon/sustechthesis/issues/32)）。
- 修复英文封面教授职称顺序错误。

## [1.3.2](https://github.com/iydon/sustechthesis/compare/v1.3.1...v1.3.2) - 2022-04-21

### Changed
- 更新英文选项，修改英文下图表名。

## [1.3.1](https://github.com/iydon/sustechthesis/compare/v1.3...v1.3.1) - 2022-03-22

### Added
- 实现可换行的条目：标题，院系，专业。

### Changed
- 更新示例文档。
- 美化超链接：移除超链接的边框。
- 修改副标题项样式：中文破折号前缀，黑体小二，右对齐。
- 将“子标题”改称“副标题”。
- 修改中英文诚信承诺书，增加可读性。

## [1.3](https://github.com/iydon/sustechthesis/compare/v1.1...v1.3) - 2022-03-17

### Added
- 初始化更新日志。

## [1.1](https://github.com/iydon/sustechthesis/compare/v1.0...v1.1) - 2021-05-08

### Added
- 开发功能。

## [1.0](https://github.com/iydon/sustechthesis/compare/v0.2...v1.0) - 2019-12-08

### Added
- 开发功能。