# 小说推文长视频流水线 · 问题反馈

用于收集小说推文长视频流水线的 BUG、功能建议和使用问题，覆盖从文本输入到配音、生图、字幕、合成和上传的各个环节。

- [主项目源码与使用说明](https://github.com/1951779219/novel_video_pipeline)
- [macOS 项目源码与使用说明](https://github.com/1951779219/novel_video_pipeline_mac)
- [主项目版本下载](https://github.com/1951779219/novel_video_pipeline_release/releases)
- [macOS 版本下载](https://github.com/1951779219/novel_video_pipeline_mac_release/releases)
- [提交反馈](https://github.com/1951779219/novel_video_pipeline_feedback/issues/new/choose)

## 如何使用

1. 搜索 [已有 Issues](https://github.com/1951779219/novel_video_pipeline_feedback/issues)，避免重复提交。
2. 选择 BUG 或功能建议模板。
3. 说明系统及软件版本、问题发生环节、复现步骤、预期和实际结果。
4. 如有任务日志，可附上 `data/jobs/<job_id>/log.txt` 尾部与错误相关的片段。
5. 在 Issue 中补充排查结果、查看回复和修复进展。

支持的分类包括启动/依赖检测、小说搜索/抓取、正文清洗/切片、TTS 配音、分镜/生图、视频合成/字幕、YouTube 上传和在线更新。创建 Issue 后，工作流会自动标记类型、优先级和相关模块。

## 隐私与日志

请先移除 API Key、Token、Cookie、账号密码、未公开正文和私人路径。反馈区是公开的，无需上传整个任务目录或浏览器登录资料。

## 仓库内容

`.github/ISSUE_TEMPLATE/` 保存反馈表单，`.github/workflows/issue_triage.yml` 和 `tools/github_issue_triage.py` 负责自动分类。本仓库无需安装；制作视频请使用对应源码项目或发行包。


## 许可

本仓库的自有代码和文档按 [MIT License](LICENSE) 提供。应用发行包中的第三方组件、工具和模型仍遵循各自许可。
