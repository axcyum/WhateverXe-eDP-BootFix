# WhateverXe-eDP-BootFix

[b00t0x/WhateverXe](https://github.com/b00t0x/WhateverXe) 0.8.2 に修正を 1 つ加えた自分用フォークです。修正は Claude Code によるものです。[English](README.md)

- **修正内容:** ファームウェアからの引き継ぎ時に内蔵 eDP のブートポートを受け入れるようにしました。内蔵 eDP パネルのノート PC（Alder Lake-N / Twin Lake など）でグラフィックスアクセラレーションが有効にならない問題への対処です。
- **状態:** CPU テストとビルドは成功しています。実機での動作確認はまだ行っていません。
- **使い方:** `python3 tools/build.py` でビルドします。必要なものと設定は[本家](https://github.com/b00t0x/WhateverXe/blob/main/README_ja.md)と同じです。
- **クレジット:** 修正は [Thatisjigen/WhateverXe `9c219ee`](https://github.com/Thatisjigen/WhateverXe/commit/9c219ee0cb56a737ecf0f3d2b1130bdc4161e8c9) を基にしています。ライセンス: BSD-3-Clause（[LICENSE.txt](LICENSE.txt)）。
