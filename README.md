# 🦋 Pink Flutter Pet

粉色蝴蝶 Codex 桌面宠物，覆盆子色轮廓、樱花粉翅膀，陪你一起工作。

![粉色蝴蝶](docs/preview.png)

## 下载与安装

1. 从 [最新 Release](https://github.com/mwyou/pink-flutter-pet/releases/latest) 下载 `pink-flutter-pet-v1.0.0.zip` 并解压。
2. 将其中的 `pink-flutter-pet` 文件夹复制到宠物目录：
   - Windows：`%USERPROFILE%\.codex\pets\`
   - macOS：`~/.codex/pets/`
3. 在支持自定义宠物的 Codex 桌面应用中打开设置 → Pets，刷新列表并选择 **Pink Flutter Pet**。不同版本的界面入口可能略有不同。

最终目录应为：

```text
pets/
└── pink-flutter-pet/
    ├── pet.json
    └── spritesheet.webp
```

也可以下载仓库源码，直接复制其中的 `pink-flutter-pet` 文件夹。若列表未更新，可重新启动应用。

## 动画预览

待机动作：

![待机动作](docs/idle.gif)

打招呼：

![打招呼](docs/waving.gif)

## 特点

- Codex v2 图集：8 列 × 11 行，1536 × 2288 像素，每格 192 × 208 像素，透明 WebP。
- 包含 9 种标准动作，以及 16 个按 22.5° 间隔排列的视线方向。
- 包含待机、打招呼、跳跃、工作等动作，双眼同步切换视线。

## 关于鼠标跟随

视线方向和鼠标悬停反应由 Codex 应用控制。当前检查的 Windows Codex `26.1021.3705.0` 未将普通鼠标位置接入宠物视线，因此此版本不会跟随普通鼠标在全桌面移动。

## 分享

把本仓库链接或 Release 压缩包发给对方，按上述步骤安装即可。该宠物包不包含也不修改 Codex 应用程序。

本项目是用户制作的自定义宠物，与 OpenAI 官方宠物发布无隶属关系。
