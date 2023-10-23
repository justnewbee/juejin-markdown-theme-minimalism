# Juejin 主题 - 极简主义

## License

MIT

## 介绍

文章就是看着清爽最好，不要过多花哨的样式和颜色，本主题特点：

1. 支持暗黑模式（暂不启用）
2. 字体粗细温和，默认 200，粗体用 400，没有 600
3. 行距、段落间距适中
4. 表格的展示能适应 90% 的展示场景（`th` 不折行、`td` 最小 72px 宽度），不至于有些内容被压缩得特别难看
5. `em` 元素为橙色
6. 包含 `<kbd>`、`<small>` 样式

## 为何不启用暗黑模式

1. `jjsm` 和掘金站点不搭配，`jjsm` 在 `html` 上加了 `.__dark`，但掘金是 body 加了 `[data-theme="dark"]`，这一点 jjsm 需要调整
2. CI 只允许 `.markdown-body` 打头的样式，于是带暗黑前缀的就会被刷下，这可能要改一下 CI 脚本吧

希望掘金官方尽早搞定，并尽早在顶栏加上主题切换入口。

## 效果图

* [亮色](minimalism-light.jpg)
* [暗色](minimalism-dark.jpg)
