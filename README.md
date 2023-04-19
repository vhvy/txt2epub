## TXT转EPUB

思路很简单：读取 TXT 文件，然后通过正则匹配章节名并切割，按照 EPUB 文件定义的结构使用 JSZIP 制作压缩包，最后以 epub 的后缀名保存即可。

参考资料： 
+ https://blog.csdn.net/qq_43257319/article/details/108530208

+ https://einverne.github.io/post/2018/09/epub-format.html