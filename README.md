# MassScope 通用版

MassScope Windows 桌面质谱软件的正式版本下载与更新页面。

当前版本：**2.0.0** · 2026-11-07 · Windows 64 位。

**[下载 2.0.0 完整包](https://github.com/k202212974/MassScope-Releases/releases/download/v2.0.0/MassScope-2.0.0-Universal-Windows-x64.zip)**

首次使用、重新安装或从任何 1.x 版本升级，均下载上面的完整包。解压至**新的程序目录**，运行 `MassScope.exe`，保留同目录的 `_internal` 文件夹。请勿覆盖旧程序目录；原有项目与实验日志可继续打开。

## 本版更新

- 分栏模式的纵轴标题按实际绘图区整体中心定位，缩放窗口、分页和 PNG／SVG 导出保持一致。
- 更新安装前主动退出当前程序，由独立更新器等待同目录所有实例和文件占用释放。占用超时则中止，原程序文件不改动。
- 先校验旧文件并完成全部备份，再安装更新；新版需通过真实启动验证，验证失败则恢复旧文件。
- 保留已下载且校验通过的更新缓存，稍后重试无需重复下载。

## 后续升级

2.0 是新的升级基线。之后可从“⋯ → 关于 → 检查更新”获取匹配当前版本的增量补丁；没有匹配补丁时使用完整包。安装前保存工作内容，并关闭同一程序目录中的其他 MassScope 窗口。

旧 1.x 发行版已归档，本页面从 2.0 开始提供正式下载。

资源中的 `.sha256`、`MassScope-update.json` 和 `.sig` 用于自动更新校验，无需单独下载。GitHub 自动生成的 `Source code` 归档不是 Windows 程序包。

[查看 2.0.0 发布说明](https://github.com/k202212974/MassScope-Releases/releases/tag/v2.0.0) · [查看最新版本](https://github.com/k202212974/MassScope-Releases/releases/latest)
