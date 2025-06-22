# CHANGELOG

## 0.1.1 2025/06/22 @驳是

* FIX 修正代码块行号问题

> 本因是 `.code-block-extension-codeLine::before` 有个 `width: 18px`，而这里 `pre` 的 `white-space: pre-wrap` 会导致其折行，
> 最佳解法是 `min-width: 18px`，但那个在掘金内部，所以这里把 `pre` 改成 `white-space: pre` 就好了。

## 0.1.0 2023/10/23 @驳是

* FEAT 第一版