# sns-post-media

SNS 自動投稿（`sns-auto-poster`）で投稿に添付する画像の置き場。

`publish.py` の `media_url` は公開 HTTP(S) URL である必要があるため
（X は画像をダウンロードし、Threads は Meta 側サーバーが URL を取得しに来る）、
ここに置いた画像の `raw.githubusercontent.com` URL を使う。

**このリポジトリの画像はすべて公開前提のもの。** 非公開にしたい画像は置かない。

## 構成

| パス | 用途 |
|---|---|
| `furusato-ledger/` | 「ふるさと納税 台帳」のリリース告知用 |

## URL の形

```
https://raw.githubusercontent.com/HiromuMorisaki/sns-post-media/main/<パス>
```
