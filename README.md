# Noiman Color Theme for VS Code

chotdekiru / noiman ブランドカラー (`#05B45B`) に揃えた VS Code テーマ。

`packages/shared-ui/src/components/domain/CodeEditor/CodeEditor.tsx` で定義している Monaco の `noiman-light` / `noiman-dark` と配色を完全一致させているので、Web 上のレッスンエディタとローカル VS Code でシンタックス表示が揃う。

## 含まれるテーマ

- **Noiman Light** — レッスン受講中のコードエディタと同じライト配色
- **Noiman Dark** — Figma 仕様のダークグリーン背景

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

## インストール (ローカル / 開発)

このパッケージは VS Code Marketplace 未公開。ローカルでインストールする場合は次の手順で。

```bash
cd packages/vscode-theme

# 1. vsce で .vsix をビルド
npx --yes vsce package --no-dependencies

# 2. 出来上がった .vsix を VS Code にインストール
code --install-extension noiman-vscode-theme-0.1.0.vsix
```

VS Code を再起動し、`Cmd+K Cmd+T` (テーマ選択) から `Noiman Light` または `Noiman Dark` を選ぶ。

## 配色を更新したら

1. `CodeEditor.tsx` の `defineTheme("noiman-light", ...)` を修正
2. このパッケージの `themes/noiman-light-color-theme.json` も同じ色に揃える
3. `version` をバンプして再ビルド + 再インストール

両方を同じトーンに保つのがこのパッケージの存在意義。
