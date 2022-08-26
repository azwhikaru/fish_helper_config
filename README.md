## 闲鱼猪手配置
> 本仓库存储原作者在停止使用前的最后一次 commit   
> 不欢迎任何倒卖、滥用、滥改

## 如何定制
- fork 本仓库
- 下载 [1.3.9_sub.apk](https://github.com/azwhikaru/fish_helper_config/blob/main/1.3.9_sub.apk)
- 使用任意反编译工具打开，例如 [MT管理器](https://www.coolapk.com/apk/21048)
- 编辑 classes.dex，全局搜索 `REPLACE_ME_TO_YOUR_REPO` 
- 将 `REPLACE_ME_TO_YOUR_REPO` 部分替换为~~你的仓库地址~~ jsDelivr 地址
- 回编译并签名

## 使用 jsDelivr
`https://cdn.jsdelivr.net/gh/用户名/仓库名@分支/文件名`   

`https://gitee.com/tpnet/fish-helper-data/raw/master/config-a40.json` ->    `https://raw.githubusercontent.com/azwhikaru/fish_helper_config/main/config-a40.json` ->   
`https://cdn.jsdelivr.net/gh/azwhikaru/fish_helper_config@main/config-a40.json` √
