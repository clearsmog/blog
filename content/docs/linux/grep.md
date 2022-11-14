---
title: "Grep"
date: 2022-10-11T21:15:03+08:00
draft: false
---

# grep命令

## 作用
查找文件中符合要求的字符串。

## 实例
```shell
grep test *file
```
在当前目录中查找后缀有file的文件中包含test字符串的文件。

```shell
grep -r update /etc/acpi
```
以递归的方式查找，指定查找目录为"/etc/acpi"
```shell
grep -v test *test*
```
反向查找，"-v" 参赛用于打印出不符合条件行的内容。
