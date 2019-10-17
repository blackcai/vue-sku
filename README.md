# vue-sku
>基于vuejs，生成一个商品sku展示组件，注意区别于[这个sku](https://github.com/rossroma/vue-sku)，他们的数据结构是不一样的，生成之后获取数据查看区别。

``
来自自动生成的规格列表：
[{ "id": 0, "name": "颜色", "list": [ { "id": "00", "value": "黄色" }, { "id": "01", "value": "黑色" } ] }, { "id": 2, "name": "尺寸", "list": [ { "id": "20", "value": "s" }, { "id": "21", "value": "l" } ] }, { "id": 3, "name": "成色", "list": [ { "id": "30", "value": "八成新" }, { "id": "31", "value": "九成新" } ] } ]
``

``
生成后的商品列表：
[ { "url": "", "sku": "00_20_30", "cost": "", "price": "", "num": "", "weight": "", "use": 1, "attr": "00_20_30" }, { "url": "", "sku": "00_20_31", "cost": "", "price": "", "num": "", "weight": "", "use": 1, "attr": "00_20_31" }, { "url": "", "sku": "00_21_30", "cost": "", "price": "", "num": "", "weight": "", "use": 1, "attr": "00_21_30" }, { "url": "", "sku": "00_21_31", "cost": "", "price": "", "num": "", "weight": "", "use": 1, "attr": "00_21_31" }, { "url": "", "sku": "01_20_30", "cost": "", "price": "", "num": "", "weight": "", "use": 1, "attr": "01_20_30" }, { "url": "", "sku": "01_20_31", "cost": "", "price": "", "num": "", "weight": "", "use": 1, "attr": "01_20_31" }, { "url": "", "sku": "01_21_30", "cost": "", "price": "", "num": "", "weight": "", "use": 1, "attr": "01_21_30" }, { "url": "", "sku": "01_21_31", "cost": "", "price": "", "num": "", "weight": "", "use": 1, "attr": "01_21_31" } ]
``

>因为是单个文件，并没有进行复杂的成份，所以没有上传到npm包服务里面，直接下载即可使用

[预览1.0](http://www.opnnn.com/sku)
初始版本的文件。


# start
```
  npm install
  npm run serve
```
访问：http://localhost:8080

##### 1.0
*更新了文件结构，使组件更清晰
