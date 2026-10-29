## 0.1.1

- Premultiply decoded AVIF alpha before handing pixels to Flutter. The engine
  treats `ui.PixelFormat.rgba8888` as premultiplied, so straight-alpha soft
  edges rendered too bright and fully transparent pixels could glow.
- Require `avif_native` ^0.2.0.

## 0.1.0

- Add memory, asset, and network AVIF widgets.
- Add animated AVIF playback and a cacheable memory image provider.
