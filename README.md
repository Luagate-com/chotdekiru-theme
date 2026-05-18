# Chotdekiru Color Theme

chotdekiru ブランドカラー (`#05B45B`) に揃えた、Monaco エディタと配色一致の VS Code / Cursor テーマセット (Light + Dark)。

Web 上の [chotdekiru.com](https://chotdekiru.com) のレッスンエディタとローカルエディタでシンタックス表示が完全に揃います。

## 動作環境

- **VS Code** (1.74 以上)
- **Cursor** (VS Code 互換なのでそのまま動作)
- その他 VS Code 拡張機能を読み込めるエディタ (VSCodium 等)

## 含まれるテーマ

- **Chotdekiru Light** — chotdekiru.com のレッスンエディタと同じライト配色
- **Chotdekiru Dark** — ブランドカラーに揃えたダークグリーン背景

## 配色 (シンタックスハイライト)

| トークン | Light | Dark |
|---|---|---|
| comment | `#8A7F73` italic | `#6A9955` italic |
| keyword (`public`, `class`, `return`) | `#F15025` | `#F97C6A` |
| string | `#D97742` | `#CE9178` |
| number / boolean / constant | `#1D6FD3` | `#B5CEA8` |
| type / class (`String`, `int`) | `#007B6E` | `#4FC67F` |
| function / method | `#05B45B` | `#7ED89D` |
| variable | `#2B2B2A` | `#E5E5E5` |

## インストール

### VS Code Marketplace から (公開後)

VS Code / Cursor の拡張機能タブで `Chotdekiru` を検索してインストール。

### .vsix を直接インストール

[Releases](https://github.com/Luagate-com/chotdekiru-theme/releases) から `.vsix` をダウンロードし、

```bash
# VS Code
code --install-extension chotdekiru-theme-0.1.0.vsix

# Cursor
cursor --install-extension chotdekiru-theme-0.1.0.vsix
```

または GUI からインストール

1. 拡張機能タブを開く (`Cmd+Shift+X`)
2. 右上の `...` メニュー → `Install from VSIX...`
3. ダウンロードした `.vsix` を選択

## テーマの選択

インストール後、`Cmd+K Cmd+T` (テーマ選択) から

- `Chotdekiru Light`
- `Chotdekiru Dark`

を選択してください。

## 他のツール向けテーマ

VS Code 以外でも同じ chotdekiru ブランドカラーを使えます。

- **[Slack](./extras/slack/README.md)** — Slack デスクトップアプリのカスタムテーマ (Light / Dark)
- **[Alacritty](./extras/alacritty/README.md)** — Alacritty ターミナルエミュレータのカラースキーム (Light / Dark)

## ライセンス

MIT
