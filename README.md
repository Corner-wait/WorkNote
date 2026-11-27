# WorkNote Android 发布仓库

「网页版工作笔记」Android 客户端公开更新与安装包分发仓库。

- **当前版本**：`v1.7.3`（`versionCode: 10703`）
- **GitHub Release 下载**：[WorkNote-1.7.3.apk](https://github.com/Corner-wait/WorkNote/releases/download/v1.7.3/WorkNote-1.7.3.apk)
- **jsDelivr 镜像下载**：[WorkNote-1.7.3.apk](https://cdn.jsdelivr.net/gh/Corner-wait/WorkNote@main/apk/WorkNote-1.7.3.apk)
- **SHA-256**：`b2ff79a6fb03e8b2211e01a9e0b604868bdfddf62ec30a2fa51389544499f6b4`

## version.json 结构

```json
{
    "versionCode":  10703,
    "versionName":  "1.7.3",
    "changelog":  "1. 手机端锁定笔记与正文宽度，取消整页横向跑偏；表格改为框内嵌入式横向滑动，并在每个超宽表格下方新增可按住左右拖拽定位的进度导航条。\n2. 优化手机端侧边栏滑出/推送动画及对称菜单图标。\n3. 笔记列表新增四种展示方式（简单列表/多行列表/小宫格/大宫格）切换面板。\n4. 明确手机端与平板端共用 Android App 版本号（v1.7.3），与网页版独立递进。",
    "apkUrl":  "https://github.com/Corner-wait/WorkNote/releases/download/v1.7.3/WorkNote-1.7.3.apk",
    "apkMirrors":  [
                       "https://cdn.jsdelivr.net/gh/Corner-wait/WorkNote@main/apk/WorkNote-1.7.3.apk"
                   ],
    "sha256":  "b2ff79a6fb03e8b2211e01a9e0b604868bdfddf62ec30a2fa51389544499f6b4"
}
```
