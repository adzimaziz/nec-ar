# NEC AR – Wind Turbine

Web AR app yang mengesan permukaan (plane detection) dan meletakkan model turbin angin 3D.

**Demo:** https://adzimaziz.github.io/nec-ar/

## Cara guna
1. Buka link di telefon — Android (Chrome, ARCore) atau iPhone (Safari, ARKit).
2. Tekan **Lihat dalam AR**.
3. Gerakkan telefon perlahan untuk kesan lantai/meja, kemudian ketik untuk letak turbin.
4. Seret untuk alih, cubit (pinch) untuk ubah saiz/putar.

## Teknologi
- [`<model-viewer>`](https://modelviewer.dev/) — WebXR hit-test (Android), Scene Viewer (Android fallback), Quick Look (iOS, USDZ dijana automatik).
- Model: `wind-turbine.glb` (dijana oleh Tripo).

AR memerlukan HTTPS — GitHub Pages sudah menyediakannya.
