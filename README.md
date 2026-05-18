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

## インストール (非エンジニアの方向け)

ターミナルを開く必要はありません。マウス操作だけで完結します。

### ステップ 1. ファイルをダウンロードする

[最新リリースページ](https://github.com/Luagate-com/chotdekiru-theme/releases/latest) を開き、`chotdekiru-theme-x.x.x.vsix` というファイルをクリックしてダウンロードしてください。

### ステップ 2. VS Code または Cursor を開く

普段使っているエディタ (VS Code または Cursor) を起動します。

### ステップ 3. 拡張機能パネルを開く

画面左の **四角が 4 つ並んだアイコン** をクリック。または `Cmd + Shift + X` (Mac) / `Ctrl + Shift + X` (Windows) を押してください。

### ステップ 4. 「VSIX からインストール」を選ぶ

拡張機能パネル右上の **「…」(三点リーダー) アイコン** をクリック → メニューから **「VSIX からインストール」** (英語表記の場合は `Install from VSIX...`) を選択。

### ステップ 5. ダウンロードした .vsix を選ぶ

ファイル選択ダイアログが開くので、ステップ 1 でダウンロードした `chotdekiru-theme-x.x.x.vsix` を選んで「インストール」をクリック。

### ステップ 6. テーマを切り替える

インストール完了後、`Cmd + K → Cmd + T` (Mac) / `Ctrl + K → Ctrl + T` (Windows) を押してテーマ選択画面を開き、次のどちらかを選んでください。

- `Chotdekiru Light` — 明るい配色
- `Chotdekiru Dark` — 暗い配色

これで完了です。

---

## インストール (エンジニア向け / コマンドライン)

```bash
# 1. .vsix をダウンロード
curl -LO https://github.com/Luagate-com/chotdekiru-theme/releases/latest/download/chotdekiru-theme-0.1.0.vsix

# 2. インストール
code --install-extension chotdekiru-theme-0.1.0.vsix   # VS Code
cursor --install-extension chotdekiru-theme-0.1.0.vsix # Cursor
```

### VS Code Marketplace から (公開後)

VS Code / Cursor の拡張機能タブで `Chotdekiru` を検索してインストール。

## 他のツール向けテーマ

VS Code 以外でも同じ chotdekiru ブランドカラーを使えます。

- **[Slack](./extras/slack/README.md)** — Slack デスクトップアプリのカスタムテーマ (Light / Dark)
- **[Alacritty](./extras/alacritty/README.md)** — Alacritty ターミナルエミュレータのカラースキーム (Light / Dark)

## ライセンス

MIT
