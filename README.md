# Rugby Overlay — 配布情報

macOS アプリ「Rugby Overlay」（ラグビー試合動画に放送風スコアボードを焼き込むアプリ）の配布情報リポジトリです。

**公式サイト（入手先・アップデート・サポート案内）**: https://shokiku.github.io/rugby-overlay/

- `latest.json` — アプリが起動時に参照する最新バージョン情報
- `sources/` — アプリに同梱しているオープンソースソフトウェアの対応ソースコード
  - `ffmpeg-6.1.2.tar.xz` — 同梱 ffmpeg / ffprobe バイナリのビルドに使用した FFmpeg のソース（LGPL v2.1+）
  - `zimg-release-3.0.5.tar.gz` — 同梱バイナリに静的リンクしている zimg のソース

同梱バイナリのビルド構成: `--disable-autodetect --enable-videotoolbox --enable-libzimg --enable-zlib`（GPL・nonfree コンポーネントは含まれません）

アプリの入手・ライセンス購入は BOOTH の商品ページから（発売準備中）。
