# Chotdekiru Alacritty Theme

[Alacritty](https://alacritty.org/) 用の chotdekiru ブランドカラーテーマ。

## インストール

```bash
# 1. テーマファイルをコピー
mkdir -p ~/.config/alacritty/themes
curl -o ~/.config/alacritty/themes/chotdekiru-light.toml \
  https://raw.githubusercontent.com/Luagate-com/chotdekiru-theme/main/extras/alacritty/chotdekiru-light.toml
curl -o ~/.config/alacritty/themes/chotdekiru-dark.toml \
  https://raw.githubusercontent.com/Luagate-com/chotdekiru-theme/main/extras/alacritty/chotdekiru-dark.toml
```

2. `~/.config/alacritty/alacritty.toml` の冒頭で import

```toml
import = [
    "~/.config/alacritty/themes/chotdekiru-light.toml",
    # "~/.config/alacritty/themes/chotdekiru-dark.toml",
]
```

Alacritty は保存時に自動ホットリロードします。
