# rime

如果一个软件的配置文件是文本，并且经常使用，就会忍不住建一个仓库同步这些配置。

### config content

- 默认候选词 9 个
- 按`Shift` 切换英文输入的时候，默认输入字母上屏
- 拼音方案只保留囧月月拼音


### ibus-rime

```bash
install -m 0644 default.custom.yaml ~/.config/ibus/rime/default.custom.yaml
```

### fcitx-rime

```bash
install -m 0644 default.custom.yaml ~/.local/share/fcitx5/rime/default.custom.yaml
```

