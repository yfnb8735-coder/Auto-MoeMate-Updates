# Auto-MoeMate Updates

本仓库仅提供 Auto-MoeMate 最新正式安装包及 Ed25519 签名更新文件，源码保持私有。

当前版本：[v0.9.95](https://github.com/yfnb8735-coder/Auto-MoeMate-Updates/releases/tag/v0.9.95)。

客户端通过"更新与导览 → 更新项目"检查并确认更新。

固定更新入口：[update.json](https://github.com/yfnb8735-coder/Auto-MoeMate-Updates/releases/latest/download/update.json)。

最新发布包含完整 Setup、对应的 `.exe.json` 和签名 `update.json`。字体及第三方组件的来源和权利说明随安装包提供。

本版本修复自动换人重登后卡在重新定位空闲灶台的问题：换人重登+换人完成后直接收口换人事件，交回正常做菜流程（有灶台派菜、没灶台识别好友印记/跑比赛、不绑定原灶台）；取消自动重连后手动开始不再死循环等待计时恢复。下载进度改为百分比显示，并放宽慢网下载时限。
