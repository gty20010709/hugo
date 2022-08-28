---
title: "Vim Markdown"
date: 2022-08-28T20:31:53+08:00
draft: false
---

- Reference: https://fokayx.com/2018/01/21/markdown-extension-on-vim.html
<br/>

## Mapping

- ]] : 前往下一個 header
- [[ : 前往上一個 header
- ][ : 前往上一個同層級 header
- [] : 前往下一個同層級 header

## Commands
在 Vim 裡面的命令列模式或者可視模式輸入指令，必須先啟用 :`filetype plug on`
- :HeaderDecrease
將所有標題各升一級，例如 h2 -> h1，在文件中已有設定 h1 的時候無法使用。如果有選取文件中的範圍，就只會作用在該選取範圍內。
- `:HeaderIncrease`
将所有标题将一级，如果已有 h6 则无法使用。
- `:Toc`
显示目录
- `:Toch`
水平显示目录
- `:Toct`
开启额外分页显示目录
