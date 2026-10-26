# 🦋 Pink Flutter Pet

粉色蝴蝶 Codex 桌面宠物，采用清晰的覆盆子色轮廓、樱花粉翅膀与双眼同步的表情。当前发布的是 **Flutter Pink Clear（稳定眼神版）**。

![粉色蝴蝶](docs/preview.png)

## 下载与安装

1. 从 [最新 Release](https://github.com/mwyou/pink-flutter-pet/releases/latest) 下载 `pink-flutter-pet-v1.0.0.zip` 并解压。
2. 将其中的 `flutter-pink-clear` 文件夹复制到宠物目录：
   - Windows：`%USERPROFILE%\.codex\pets\`
   - macOS：`~/.codex/pets/`
3. 在支持自定义宠物的 Codex 桌面应用中打开设置 → Pets，刷新列表并选择 **Flutter Pink Clear（稳定眼神版）**。不同版本的界面入口可能略有不同。

最终目录应为：

```text
pets/
└── flutter-pink-clear/
    ├── pet.json
    └── spritesheet-stable-eyes.webp
```

也可以下载仓库源码，直接复制其中的 `flutter-pink-clear` 文件夹。更新旧版前请备份自己的同名宠物目录，再替换这两个文件。若画面未更新，可切换到其他宠物后再切回，必要时重新启动应用。

## 动画预览

待机动作：

![待机动作](docs/idle.gif)

打招呼：

![打招呼](docs/waving.gif)

## 当前版本

- Codex v2 图集：8 列 × 11 行，1536 × 2288 像素，每格 192 × 208 像素，透明 WebP。
- 包含 9 种标准动作，以及 16 个按 22.5° 间隔排列的视线方向。
- 已修复旧素材中待机歪脸、工作侧眼和完成提示歪头的突兀画面，保留双眼同步的视线帧。
- 发布素材与当前安装的稳定眼神版逐字节一致，v2 图集校验通过，无错误、无警告。

## 关于鼠标跟随

**这份素材不提供普通实体鼠标的全桌面视线跟随功能。**

检查 Windows Codex `26.1021.3705.0` 的运行时代码发现，宠物的视线目标来自 Computer Use 光标或输入框插入点；普通鼠标位置没有接入该目标路径。16 个方向帧已经包含在图集中，是否触发由 Codex 应用决定。增加图片帧数无法补上鼠标坐标来源。

鼠标悬停时的跳跃反应、状态切换和动作重复由应用控制。图集校验通过不代表实体鼠标跟随已通过桌面实测。后续应用版本可能改变这些行为。

## 分享

把本仓库链接或 Release 压缩包发给对方，按上述步骤安装即可。该宠物包不包含也不修改 Codex 应用程序。

本项目是用户制作的自定义宠物，与 OpenAI 官方宠物发布无隶属关系。
