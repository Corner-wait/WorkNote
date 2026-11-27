# WorkNote Android 发布仓库

「网页版工作笔记」Android 客户端公开更新与安装包分发仓库。

- **当前版本**：`v1.7.2`（`versionCode: 10702`）
- **GitHub Release 下载**：[WorkNote-1.7.2.apk](https://github.com/Corner-wait/WorkNote/releases/download/v1.7.2/WorkNote-1.7.2.apk)
- **jsDelivr 镜像下载**：[WorkNote-1.7.2.apk](https://cdn.jsdelivr.net/gh/Corner-wait/WorkNote@main/apk/WorkNote-1.7.2.apk)
- **SHA-256**：`34fa68a955c4848d6cd0109a7c81a0064f11ecd1393dbaad5087a39091efaed9`

## version.json 结构

```json
{
    "versionCode":  10702,
    "versionName":  "1.7.2",
    "changelog":  "v1.7.2：加固应用内更新下载与校验链路（新增 3 轮递增退避重试、Content-Length 完整性校验、jsdelivr 多源镜像回退、修复流读取边界并区分下载与校验失败提示）。",
    "apkUrl":  "https://github.com/Corner-wait/WorkNote/releases/download/v1.7.2/WorkNote-1.7.2.apk",
    "apkMirrors":  [
                       "https://cdn.jsdelivr.net/gh/Corner-wait/WorkNote@main/apk/WorkNote-1.7.2.apk"
                   ],
    "sha256":  "34fa68a955c4848d6cd0109a7c81a0064f11ecd1393dbaad5087a39091efaed9"
}
```
