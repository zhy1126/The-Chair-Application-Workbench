# The Chair Application Workbench

一个简洁、免费开源、可离线使用的研究生申请追踪表。公开版本使用虚构学校与示例数据，不包含个人申请清单。

**[下载 Mac / Windows 通用离线 ZIP](The-Chair-Application-Workbench-v1.0.1-offline.zip?raw=true)**

## 使用

1. 下载并解压 ZIP。
2. 双击文件夹内的 `index.html`，用浏览器打开。
3. 顶部工具栏支持按地区或截止时间排序、选择项目并调整行颜色。
4. 每条记录可选择“未开始”“准备中”或“已提交”。

无需安装、注册或网络；打开外部项目链接时才需联网。Mac 和 Windows 使用同一个 ZIP。

## 填入自己的项目

当前学校、日期、费用与要求均为虚构示例，链接指向 example.com。用文本编辑器打开 `index.html`，修改 `const applications` 列表；常用字段为 `school`、`program`、`ddl`（YYYY-MM-DD）、`fee`、`req` 和 `programUrl`。新增记录时按相同格式添加对象，`region` 可使用 `singapore`、`hong-kong`、`us` 或 `uk`。如维护 `dist` 副本，请同步更新。

目前界面直接支持编辑状态与颜色；其余项目内容在源码中修改。请自行核对真实申请的官方日期、费用、要求和链接。

## 本地数据

状态和颜色保存在当前浏览器，不会上传。更换浏览器、移动文件位置或清除浏览器数据后，这些设置可能无法保留。需要迁移时请自行记录状态。公开示例使用独立的浏览器存储键。

分发自己修改过的版本前，请检查其中是否含有个人申请信息。公开模板没有包含任何简历、申请文件或个人浏览器数据。

## 开源

源码为根目录的 `index.html`；`dist/index.html` 是相同页面副本。单文件 HTML/CSS/JavaScript，无构建步骤或外部依赖。代码采用 [MIT License](LICENSE)。
