# Juno ACR

AEAssist 青魔法师 ACR，由 Juno 维护。本仓库只提供编译后的插件和更新说明。

[下载最新版本](https://github.com/xiaozhunuonuode/Juno-ACR/releases/latest) · [查看全部版本](https://github.com/xiaozhunuonuode/Juno-ACR/releases)

## 首次安装

1. 下载 Release 中的 Juno-ACR.zip。
2. 停用当前 JunoBlueMage ACR，并将原 DLL 备份到 ACR 目录之外。
3. 解压后把 Juno 文件夹放到 AEAssist 的 ACR 目录，使文件位于 ACR/Juno/Juno.dll；旧安装目录请先移出 ACR，避免重复加载。
4. 在 AEAssist 中重新加载本地 ACR，作者选择 Juno。

## 后续更新

打开 JunoBlueMage 的“版本更新”页，检查新版本并阅读说明，再点击“下载安装”。
安装完成后使用 /aeReload 重新加载本地 ACR，才会使用新版本；尚未重载时，当前运行的仍是旧版。
更新只替换本插件 DLL，保留本地设置，并在设置目录备份旧 DLL。
旧发布仓库已停用。此前安装过 1.1.0 的用户需要从本仓库手动下载并安装一次；若从旧目录迁移，请将旧目录移出 ACR 并完整重启游戏，避免 AE 保留旧的加载记录。之后即可使用本版本的内置更新。

本下载包不包含 AEAssist、Dalamud 或可选 DR 模块，请使用自己的现有环境。
