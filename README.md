# Readthis API 文档

[Readthis](http://100000p.com)

[功能点](https://github.com/zhangshanhai/readthis-web/blob/master/README.md)

[手绘图](https://github.com/zhangshanhai/readthis-web/blob/master/img/index.md)

## API 文档

[注册](https://github.com/zhangshanhai/readthis-api/blob/master/doc/register.md)√

[授权](https://github.com/zhangshanhai/readthis-api/blob/master/doc/authorization.md)√


[时间线](https://github.com/zhangshanhai/readthis-api/blob/master/doc/timelines.md)√

[文章](https://github.com/zhangshanhai/readthis-api/blob/master/doc/articles.md)√


[根据url查文章](https://github.com/zhangshanhai/readthis-api/blob/master/doc/bases.md)√


[用户](https://github.com/zhangshanhai/readthis-api/blob/master/doc/users.md)


[个性域名](https://github.com/zhangshanhai/readthis-api/blob/master/doc/url-tokens.md)


[微刊](https://github.com/zhangshanhai/readthis-api/blob/master/doc/collections.md)√


[标签](https://github.com/zhangshanhai/readthis-api/blob/master/doc/tags.md)


[远程页面](https://github.com/zhangshanhai/readthis-api/blob/master/doc/remote-pages.md)√

## 设计规范

Readthis 的 API 遵循[现代 RESTful API 设计规范](https://github.com/BlackGlory/modern-restful-api-design-specification).


## api约定

1.请求list列表时 都需要带上参数，size。
返回时，头部都会返回 count: 个数。

2.如果查询只要id，则 在原来地址请求的对象下 加 _id 即可。**文档中没有体现**

> 例如 /v2/collections/:collectionId/articles_id  表示查某一微刊下的所有文章的id。


## 讨论

[![](http://pub.idqqimg.com/wpa/images/group.png "用户交流群")](http://shang.qq.com/wpa/qunwpa?idkey=bc60b852e963704404153f225800257ab64dc5727cab6e777166f7d76046ba7a)
