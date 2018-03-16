用户可以在Notebook页面的CodeCell中输入pip指令查询、安装、更新工具包。

* Python2 环境下

```
%%bash
pip2 list --format=columns  #查看Kernel下所有预置的工具包
pip2 show package_name      #查看Kernel是否有某个工具包
```

* Python3 环境下

```
%%bash
pip list --format=columns  #查看Kernel下所有预置的工具包
pip show package_name      #查看Kernel是否有某个工具包
```