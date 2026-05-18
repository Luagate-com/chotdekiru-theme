# Chotdekiru Color Theme

chotdekiru ブランドカラー (`#05B45B`) に揃えた VS Code / Cursor 用のカラーテーマ (Light + Dark)。

Web 上の [chotdekiru.com](https://chotdekiru.com) のレッスンエディタとローカルエディタで、シンタックスの配色が完全に揃います。

## 動作環境

- **VS Code** (1.74 以上)
- **Cursor** (VS Code 互換)

## 含まれるテーマ

- **Chotdekiru Light** — chotdekiru.com のレッスンエディタと同じライト配色
- **Chotdekiru Dark** — ブランドカラーに揃えたダークグリーン背景

## インストール手順

### ステップ 1. ファイルをダウンロードする

[最新リリース](https://github.com/Luagate-com/chotdekiru-theme/releases/latest) を開き、`Assets` セクションの `chotdekiru-theme-0.1.0.vsix` をクリックしてダウンロードします。

### ステップ 2. VS Code または Cursor を開く

普段使っているエディタを起動します。

### ステップ 3. 拡張機能パネルを開く

画面左の **四角が 4 つ並んだアイコン** をクリック。または `Cmd + Shift + X` (Mac) / `Ctrl + Shift + X` (Windows)。

### ステップ 4.「VSIX からインストール」を選ぶ

拡張機能パネル右上の **「…」(三点リーダー)** をクリック → **「VSIX からインストール」** (英語表記は `Install from VSIX...`) を選択。

### ステップ 5. ダウンロードした .vsix を選ぶ

ステップ 1 でダウンロードした `chotdekiru-theme-0.1.0.vsix` を選んで「インストール」をクリック。

### ステップ 6. テーマを切り替える

`Cmd + K → Cmd + T` (Mac) / `Ctrl + K → Ctrl + T` (Windows) でテーマ選択を開き、次のいずれかを選択。

- `Chotdekiru Light`
- `Chotdekiru Dark`

完了です。

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

## 他のツール向けテーマ

VS Code 以外でも同じ chotdekiru ブランドカラーを使えます。

- **[Slack](./extras/slack/README.md)** — Slack デスクトップアプリのカスタムテーマ (Light / Dark)
- **[Alacritty](./extras/alacritty/README.md)** — Alacritty ターミナルエミュレータのカラースキーム (Light / Dark)

## ライセンス

MIT
