# dsh-startup-screen-mecha

机甲主题的 **DeepSeek Harness** 启动界面 / 启动动画插件（2号b · 亮眼版）。

黑幕厂牌 → 过曝洗白 → 机甲座舱（白蓝机甲 + 目镜呼吸辉光 + 右侧 HUD）
→ 可交互的五步授权 → 欢迎页。机甲图片已内嵌在插件里，不需要额外素材。

## 效果

- 第一幕黑屏与第一页保持原样（深度求索 / DEEPSEEK）
- 第二幕起切进机甲座舱：白蓝机甲居中放大，目镜发光，交互按钮压在胸口核心上
- 交互都有声音：身份卡可逐项点选核验、第三幕选接驳协议（标准 / 静默 / 全功率）
- 桌面端播放期间标题栏透明，播放结束自动还原

## 安装

**下载 Release 里的 tgz，然后：**

```bash
dsh plugin --profile desktop add "下载到的路径/dsh-startup-screen-mecha-1.3.0.tgz"
```

浏览器版把 `desktop` 换成 `web`。装完重启 DeepSeek Harness Desktop。

## 自定义

设置 →「启动动画」：身份名称 / 编号 / 权限等级 / 主题 / 文案 / 音量 / 语速。

## 说明

- 需要 dsh 0.2.x 及以上（支持插件 bundle 的桌面端或 web profile）
- 插件本体基于 dsh-startup-screen（MIT，原作者：沈宏宏），本仓库只改了文案与视觉
- 机甲图片由本仓库作者提供，请勿另行转载
