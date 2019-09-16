# 文档说明

## 构建

- 安装`gitbook-cli`

```
cnpm install gitbook-cli -g
```

- 在当前目录下，安装`book.json`里面的插件，生成`node_modules`目录

```
gitbook install
```

- 在当前目录下，执行`gitbook`构建，生成`_book`目录（源文件）

```
gitbook build
```

完成后，生成的`_book`目录即为`html`目标代码

## 其他

- 设置一下`.gitignore`，将`_book`和`node_modules`文件夹屏蔽上传

## 版本

- V1.0 2019年9月13日 16:49:12
    - 初建文档
    - 一周一更