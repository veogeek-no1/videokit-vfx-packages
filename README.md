# videokit-vfx-packages

A community-shared VFX package registry for VideoKit. Includes shader filters, transitions, text animations, AI inference effects, LUTs, audio assets, and more.

## Repository Structure

```
packages/
  <package-name>/
    <version>/
      manifest.json    ← package declaration (see format below)
      <assets...>      ← shaders, models, LUTs, audio, etc.
```

## Usage

```bash
git clone https://github.com/veogeek-no1/videokit-vfx-packages.git
```

After cloning, rebuild the local index with the VideoKit tooling (coming soon).

## Contributing

1. Fork this repository
2. Add your `manifest.json` and asset files under `packages/<your-package-name>/<version>/`
3. Open a PR — no merge conflicts since every package lives in its own directory

## Manifest Format

See the [VideoKit VFX Package Spec](https://github.com/veogeek-no1/video-kit/blob/main/docs/design/vfx-package.md).
