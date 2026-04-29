# liberte-link-hub

NPO法人リベルテの公式リンクハブサイト（lit.link型シングルサイト）。

- **公開URL**: <https://link.npo-liberte.org/>
- **公式サイト**: <https://npo-liberte.org/>

## 構成

- 静的HTML（ビルド不要）
- [Cloudflare Pages](https://pages.cloudflare.com/) でホスティング
- カスタムドメイン: `link.npo-liberte.org`

## ファイル構成

```text
.
├── index.html                  # シングルページ本体
├── assets/
│   ├── logo.svg                # 正方形ロゴ
│   ├── logo-horizontal.svg     # 横長ロゴ
│   ├── bg-color.png            # 背景パターン（カラー）
│   └── bg-mono.png             # 背景パターン（モノクロ）
└── README.md
```

## 編集と公開

```bash
# 編集
git clone https://github.com/rojo-works/liberte-link-hub.git
cd liberte-link-hub
# index.html を編集

# 公開
git add .
git commit -m "更新内容"
git push
```

push後、Cloudflare Pages が自動で再デプロイする（数十秒で本番反映）。

## ライセンス

NPO法人リベルテ
