---
title: "我的终端配置和美化CMD和PowerShell的方法"
date: 2022-04-01T21:43:29+08:00
---

## 美化power shell和cmd

powershell可以直接用[ohmyposh](https://ohmyposh.dev/)美化

cmd使用[clink](https://chrisant996.github.io/clink/)简单美化+添加补全功能即可（[ohmyposh](https://ohmyposh.dev/)虽然也能给cmd用，但实测[ohmyposh](https://ohmyposh.dev/)会影响cmd启动速度，不建议安装；而powershell启动本来就不快，适合用omp）



## 现在我的终端配置是：

1. 日用：WSL1 Alpine(zsh + omz) 

   可以混合使用Linux 和 Windows命令太爽了

2. 开发：WSL2 Ubuntu(zsh + omz) 

   开发还是在纯Linux环境舒服，不容易有稀奇古怪的错误

3. 执行bat：cmd(clink)

   兼容执行一些bat和cmd脚本的时候用

4. 备用：powershell(ohmyposh)

   暂时没怎么学C#，所以感受不到Powershell的强大，只用来执行ps1脚本用过。。。感觉叫PowerScript更贴切。。。