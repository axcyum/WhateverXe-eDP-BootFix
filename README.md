# WhateverXe-eDP-BootFix

Personal fork of [b00t0x/WhateverXe](https://github.com/b00t0x/WhateverXe) 0.8.2 with one fix, written with Claude Code. [日本語](README_ja.md)

- **Fix:** the internal eDP boot port is now accepted at the firmware handoff, so laptops with a built-in eDP panel (e.g. Alder Lake-N / Twin Lake) are no longer left without graphics acceleration.
- **Status:** CPU tests and the build pass; not yet verified on real hardware.
- **Usage:** build with `python3 tools/build.py`. Requirements and setup are the same as [upstream](https://github.com/b00t0x/WhateverXe#readme).
- **Credits:** fix based on [Thatisjigen/WhateverXe `9c219ee`](https://github.com/Thatisjigen/WhateverXe/commit/9c219ee0cb56a737ecf0f3d2b1130bdc4161e8c9). WhateverXe retains WhateverGreen's copyright notices and BSD-3-Clause license ([LICENSE.txt](LICENSE.txt)); all other credits are listed in the [upstream README](https://github.com/b00t0x/WhateverXe#license-and-credits).
