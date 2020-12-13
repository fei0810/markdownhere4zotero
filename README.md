## 使用效果

![](https://raw.githubusercontent.com/fei0810/image-host/master/img/20190914114547.gif)

## 源文件

markdown here github https://github.com/adam-p/markdown-here

## Zotero 插件制作

Zotero 的插件格式和 Firefox 一致，后缀为 xpi，但是本质其实是一个 zip 压缩文件

新建一个目录`markdownhere4zotero`包含如下内容

```
chrome.manifest
install.rdf
common/
firefox/
```

在该目录下进行 zip 即可

```sh
zip -r ./markdownhere4zotero.zip ./
```

然后修改 `markdownhere4zotero.zip` 为 `markdownhere4zotero.xpi` 即可。

## 使用

下载xpi格式文件，然后按照正常插件安装即可
