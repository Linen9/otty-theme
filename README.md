# otty-theme

Linen 系列主题，适配 [otty](https://github.com/otty-shell/otty) 终端模拟器。

Linen theme family for the [otty](https://github.com/otty-shell/otty) terminal emulator.

---

## 安装 / Install

下载 `.ottytheme` 文件放入 otty 主题目录：

Download the `.ottytheme` file(s) and place them in the otty themes directory:

```
~/.config/otty/themes/
```

然后在 otty 偏好设置中选择主题，或在配置文件中指定：

Then select the theme in otty preferences, or set in `~/.config/otty/config.toml`:

```toml
# 浅色模式 / Light mode
theme = "Linen"

# 深色模式 / Dark mode
theme-dark = "Linen Dark"
```

## 主题 / Themes

| 主题 Theme | 模式 Mode | 说明 Description |
|-----------|-----------|-----------------|
| Linen | 浅色 Light | 暖调纸感浅色主题 — 奶油底色，橙棕强调色 / Warm paper-toned — cream background, orange-brown accents |
| Linen Dark | 深色 Dark | 暖调炭灰深色主题 — 烟熏棕黑底色，柔和植物色系 / Warm charcoal — smoky brown-black, muted botanical colors |

## 推荐 otty 配置 / Recommended otty Settings

以下配置与 Linen 主题搭配使用效果最佳：

The following settings pair best with the Linen themes:

| 配置项 Key | 推荐值 Value | 说明 Notes |
|-----------|-------------|-----------|
| `font-blending` | `"linear"` | 灰度抗锯齿，小字号下避免彩色边缘 / Grayscale AA, avoids color fringing at small sizes |
| `cursor-style` | `"bar"` | 竖线光标视觉干扰最小，终端重度用户首选 / Least visual weight, preferred by power users |
| `terminal-scroll-smooth` | `true` | 平滑滚动，otty Metal 后端开销极低 / Smooth scrolling, near-zero overhead on Metal |
| `shell-integration` | `true` | 启用命令块标记、退出码提示、快速启动联动 / Command blocks, exit codes, Quick Launch integration |
| `background-opacity` | `0.92` | 微透明增加层次感，不损文字对比度 / Subtle depth without compromising contrast |
| `window-layout` | `"tabs-top"` | 顶部标签栏最符合直觉，不易遗漏多会话 / Most discoverable tab layout |
| `auto-hide-tab-bar` | `"auto"` | 单标签时自动隐藏，节省纵向空间 / Reclaims vertical space with a single tab |

## 许可 / License

MIT — 详见 [LICENSE](LICENSE)。
