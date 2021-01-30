### Conclusion of software:

##### 1 Typora 

1.1  Add right click

#**https://www.cnblogs.com/zhoujiayingvana/p/12357812.html**

新建一个`txt`文本文件，写入：

```
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\.md]
@="Typora.md"
"Content Type"="text/markdown"
"PerceivedType"="text"

[HKEY_CLASSES_ROOT\.md\ShellNew]
"NullFile"=""
```

然后修改`.txt`后缀为`.reg` 的注册表文件。

然后双击运行。

