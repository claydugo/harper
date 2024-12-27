---
title: Helix Support
---

To use Harper in [Helix](https://helix-editor.com/), you'll need to have `harper-ls` installed.

Once you do, add this to you configuration:

```toml
[language-server.harper-ls]
command = "harper-ls"
args = ["--stdio"]
```