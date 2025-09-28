# NGINX AUTOINDEX 配置

## 如何使用

将 /conf 和 /html 复制到 nginx 目录下即可实现美化

## 其他

1. 通过 `add_body_after` 来实现，项目根路径下所有除了 `views` 子目录的文件，都会配置`add_body_after`，来实现美化目录结构的目的。
2. 不通过 `fancyindex` 插件来实现，因为还要编译太麻烦。
3. 不希望显示的文件，可以命名为以 . 开头命名，例如 `.[原文件名].[文件格式]`。

