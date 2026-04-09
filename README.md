# nicenail-staff-photos

ナイスネイル スタッフ写真管理リポジトリ

## 写真の追加方法

1. `photos/` フォルダに写真をアップロード
2. 次回の `deploy_auto.sh` 実行時に自動でダッシュボードに反映

## ファイル名ルール

- 先頭の記号（■□●▲★◆）は除去
- `*` はそのまま残す（同名スタッフの区別用）
- 拡張子は `.jpg`

### 例

| Salon Connect上の名前 | ファイル名 |
|---|---|
| ●Aoi | `Aoi.jpg` |
| □Karen* | `Karen*.jpg` |
| Yuuka | `Yuuka.jpg` |
| Yuuka* | `Yuuka*.jpg` |
| Yuuka** | `Yuuka**.jpg` |
| ■Akane | `Akane.jpg` |

## 写真の仕様

- 正方形推奨（ダッシュボードでは丸くトリミングされます）
- 推奨サイズ: 200x200px 以上
- 形式: JPEG (.jpg)
