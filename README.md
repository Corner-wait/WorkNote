# WorkNote Android 发布仓库

「网页版工作笔记」Android 客户端公开更新与安装包分发仓库。

- **当前版本**：`v1.7.5`（`versionCode: 10705`）
- **GitHub Release 下载**：[WorkNote-1.7.5.apk](https://github.com/Corner-wait/WorkNote/releases/download/v1.7.5/WorkNote-1.7.5.apk)
- **jsDelivr 镜像下载**：[WorkNote-1.7.5.apk](https://cdn.jsdelivr.net/gh/Corner-wait/WorkNote@main/apk/WorkNote-1.7.5.apk)
- **SHA-256**：`c22b6f157dba04968dc0934e6080ee7655cea1d9a90abac677249da5c820fd2f`

## version.json 结构

```json
{
    "versionCode":  10705,
    "versionName":  "1.7.5",
    "changelog":  "1. 手机端同步弹窗精简缩小约一半，合并为「仓库路径 + Git 令牌」，移除小字说明，测试连接与复制日志移入高级操作，三主操作单行并排、关闭放右下角。\n2. 笔记大宫格修复为按小宫格 4:5 比例等比放大渲染，正常展示真实正文缩略内容与标题；全端列表支持微缩排版与圆角/调色优化。\n3. 自定义光标水滴：单点呼出含「选择」菜单，短按拖动保留放大镜精准调位，长按直接滑动选字。\n4. 阅读态支持直接勾选/取消待办；编辑态勾选待办或目录跳段均不弹键盘，仅点击正文文字/标题呼出软键盘；全面屏底栏下移 9pt。",
    "apkUrl":  "https://github.com/Corner-wait/WorkNote/releases/download/v1.7.5/WorkNote-1.7.5.apk",
    "apkMirrors":  [
                       "https://cdn.jsdelivr.net/gh/Corner-wait/WorkNote@main/apk/WorkNote-1.7.5.apk"
                   ],
    "sha256":  "c22b6f157dba04968dc0934e6080ee7655cea1d9a90abac677249da5c820fd2f"
}
```
