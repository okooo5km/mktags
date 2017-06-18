# mktags

mktags是一个shell脚本编写的工具，可以帮助生成mcu工程完整的cscope和ctags索引。

### 安装

```
git clone https://github.com/smslit/mktags /temp/mktags
cp /temp/mktags /usr/local/bin
```

### 使用

包含info、build、clean、help四个子命令，其中build和info后续需要跟参数，即MCU平台名称。

### 定制

修改脚本中listSources函数，添加对应MCU平台的listSources函数，函数中的路径根据MCU平台决定！同时更新一下usageInfo和mcuInfo。
