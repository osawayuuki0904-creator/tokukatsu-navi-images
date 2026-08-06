# tokukatsu-navi-images

トク活ナビ（Threads運用）の投稿用生成画像の置き場。

- 本体リポジトリ: osawayuuki0904-creator/tokukatsu-navi の `openai_image.py` が自動でアップロードする
- **public 必須**: Threads(Meta) が認証なしで画像を取得しに来るため。private にすると「投稿は通るのに画像だけ映らない」静かな失敗になる
- パス規則: `<account>/<年>/<account>_<slug>.jpg`
