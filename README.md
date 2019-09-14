## 源文件

markdown here github https://github.com/adam-p/markdown-here

## zotero 插件制作

zotero 的插件格式和Firefox一致，后缀为xpi，但是本质其实是一个zip压缩文件

新建一个目录`markdownhere4zoter`包含如下内容

```
chrome.manifest
install.rdf
common/
firefox/
```

在该目录下进行zip即可

```sh
zip -r ./markdownhere4zoter.zip ./
```
