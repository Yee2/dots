### install

在当前目录下面执行命令安装配置：

```bash
install -m 0644 alacritty.toml ~/.config/alacritty/alacritty.toml
```

### fonts

默认字体使用 JetBrainsMono Nerd 版本，需要[下载](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/JetBrainsMono.zip)，然后解压到 `~/.local/share/fonts` 目录。

```bash
mkdir -p ~/.local/share/fonts
mv *.ttf ~/.local/share/fonts
fc-cache -fv
```
