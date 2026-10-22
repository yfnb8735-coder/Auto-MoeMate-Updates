# Auto-MoeMate Updates

此公开仓库仅分发 Auto-MoeMate 的受保护安装程序、签名更新清单和发布说明。项目源码在独立私有仓库维护。

## 在线更新测试

计划测试路径：Test v0.1 → Test v0.2。测试版使用独立安装位置和数据目录，测试发布不得用于正式版更新。

修正版 Test v0.2 已发布至 [Releases](https://github.com/yfnb8735-coder/Auto-MoeMate-Updates/releases/tag/test-v0.2)，供 Test v0.1 在线升级验收。实际更新助手安装与启动回执已通过，冻结窗口点击全链路待用户实测。

客户端匿名下载公开附件，并使用内置公钥验证发布签名及文件完整性。仓库不存放用户配置、真实卡密、访问令牌或签名私钥。

程序所含第三方组件、字体及资源的权利说明随安装包提供。
## 正式在线更新

[v0.8.5](https://github.com/yfnb8735-coder/Auto-MoeMate-Updates/releases/tag/v0.8.5) 已作为最新正式版发布。正式客户端固定匿名读取同名 update.json，受保护安装包及索引均使用既有 Ed25519 更新签名。请从本轮重建的 v0.8.3 安装版进入“更新与导览 → 更新项目”进行升级验证；历史同版本安装包不具备相同更新能力。正式安装升级由用户实机确认。