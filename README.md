# ParallelAssetLoader

- Rustの標準ライブラリだけを使って作った，**並列アセットローダ＋簡易ゲームループ**です．

---


<!--

## 🔍 このプロジェクトでやっていること

- `std::thread` と `mpsc` を使った**並列ファイル読み込み**
- `Instant::now()` を使って読み込み時間を測定し、**逐次 vs 並列**を比較
- シンプルな**固定フレームレートのゲームループ**（30FPS）
- ゲーム的な「ロード完了→描画開始」みたいな流れの再現

---

## 📦 使っているもの

- Rust（標準ライブラリのみ）
- Cargo（ビルドツール）
- アセットは `.txt` や `.json` のダミーファイルを自作しています

---

-->


## ▶️ 実行方法

```bash
git clone https://github.com/yourusername/ParallelAssetLoader.git
cd ParallelAssetLoader
cargo run --release
