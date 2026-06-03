# videokit-vfx-packages

VideoKit 共享 VFX 包仓库。收录 shader 滤镜、转场、文字动画、AI 推理效果、LUT、音效素材等。

## 目录结构

```
packages/
  <package-name>/
    <version>/
      manifest.json    ← 包声明文件（格式见下）
      <资源文件…>      ← shader、模型、LUT、音频等
```

## 如何使用

```bash
git clone https://github.com/veogeek-no1/videokit-vfx-packages.git
```

克隆后本地重建索引（工具待发布）。

## 如何贡献

1. Fork 本仓库
2. 在 `packages/<your-package-name>/<version>/` 下新增 `manifest.json` 及资源文件
3. 提 PR，不会与他人产生冲突（每个包独立目录）

## Manifest 格式

参见 [VideoKit VFX Package 规范](https://github.com/veogeek-no1/video-kit/blob/main/docs/design/vfx-package.md)。
