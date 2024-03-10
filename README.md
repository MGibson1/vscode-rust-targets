Forked from [PolyMeilex](https://github.com/PolyMeilex/vscode-rust-targets) to update a few behaviors.

# VSCode Rust Targets

[![badge](https://img.shields.io/visual-studio-marketplace/i/polymeilex.rust-targets?label=vs%20marketplace&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=PolyMeilex.rust-targets)

Super simple extension to change rust target in VS Code without opening `setting.json`

![img](https://i.imgur.com/4XVZ5ko.png)
![img](https://i.imgur.com/UAszh6C.png)

Written only for personal use, but maybe someone else also needs it, so here it is.
Enjoy!

# Settings

You can configure target list by adding this to your `settings.json`

Choosing `system` will remove a specified setting, which in consequence sets your target to your current host system.

```json
"rust-analyzer-targets.targets": [
    "system",
    "x86_64-pc-windows-gnu",
    "x86_64-apple-darwin",
    "wasm32-unknown-unknown",
    "x86_64-unknown-linux-gnu"
]
```
