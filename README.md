# SEU-Thesis-Download (东南大学硕博论文下载助手)
<div align="center">
  <a href="https://github.com/kanhao100/SEU-Thesis-Download" style="text-decoration: none;">
    <img src="https://img.shields.io/github/stars/kanhao100/SEU-Thesis-Download?style=flat-square&logo=github" alt="GitHub Stars">
  </a>
  <a href="https://greasyfork.org/zh-CN/scripts/560893-seu-thesis-download" style="text-decoration: none;">
    <img src="https://img.shields.io/greasyfork/v/560893?style=flat-square&logo=tampermonkey" alt="GreasyFork Version">
  </a>
  <a href="https://greasyfork.org/zh-CN/scripts/560893-seu-thesis-download" style="text-decoration: none;">
    <img src="https://img.shields.io/greasyfork/dt/560893?style=flat-square&logo=greasyfork" alt="Total Downloads">
  </a>
  <a href="https://github.com/kanhao100/SEU-Thesis-Download/blob/main/LICENSE" style="text-decoration: none;">
    <img src="https://img.shields.io/github/license/kanhao100/SEU-Thesis-Download?style=flat-square" alt="License">
  </a>
</div>

<img width="1116" height="199" alt="Snipaste_2025-12-31_13-37-48" src="https://github.com/user-attachments/assets/6fa26430-74be-441c-9133-0389d8f7c913" />

这是一个专门针对 **[东南大学学位论文数据库 (223.3.67.16)](https://lib.seu.edu.cn/bencandy.php?fid=250&id=1464)** 开发的油猴 (Tampermonkey) 脚本。
它能够在论文详情页直接注入下载按钮，绕过在线预览的打印和导出限制，且是原始格式可以进行复制，并根据论文信息自动重命名文件，极大地提升了科研文献的整理效率。


## 安装指南

### 第一步：安装脚本管理器

你需要先安装用户脚本管理器。如果你已经安装了，请跳过此步。
* **Chrome**: [Tampermonkey (油猴)](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
* **Edge**: [Tampermonkey (篡改猴)](https://microsoftedge.microsoft.com/addons/detail/%E7%AF%A1%E6%94%B9%E7%8C%B4/iikmkjmpaadaobahmlepeloendndfphd)
* **Firefox**: [Tampermonkey](https://addons.mozilla.org/zh-CN/firefox/addon/tampermonkey/)

### 第二步：安装脚本

#### 方法 A：手动添加 (推荐)

1. 点击浏览器右上角的 Tampermonkey 图标。
2. 选择 **“添加新脚本...”**。
3. 删除编辑器中所有默认代码。
4. 复制本项目中的 `seu-thesis-downloader.user.js` 代码。
5. 粘贴到编辑器中，按 `Ctrl + S` 保存。

#### 方法 B：从 GreasyFork 安装 （可能需要魔法）

* [点击这里安装脚本](https://greasyfork.org/zh-CN/scripts/560893-seu-thesis-download)

## 使用说明

1. 访问东南大学硕博士论文数据库[http://223.3.67.16/tpi65](http://223.3.67.16/tpi65)。
2. 搜索并点击进入任意一篇论文的 **详情页**。
3. 等待页面加载完成（约 1 秒），你会发现“在线预览”按钮右侧多了一个绿色的 **“立即下载”** 按钮。
4. 点击下载，脚本会自动解析并保存为规范命名的 PDF 文件。

## ⚠️ 免责声明
* 本工具仅供 **东南大学内部师生科研学习** 使用，非内部账号只能阅读前16页。
* 请勿使用本工具进行批量爬取或商业用途，由此产生的账号封禁或法律风险由使用者自行承担。
* 脚本未修改任何服务器数据，仅在本地浏览器端运行。


