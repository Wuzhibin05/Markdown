# 图片

### 1，定义格式

Markdown 支持两种形式的图片语法： **行内式**和**参考式**两种形式。

**行内式**

- 一个惊叹号 !
- 接着一个方括号，里面放上图片的替代文字
- 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上 选择性的 'title' 文字。

```shell
# 本地图片
![赵丽颖1](../picture/zly.jpg)
# 网络图片
![赵丽颖2](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560405174093&di=c86d019653e9d7e8db08627fded4a2f5&imgtype=0&src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201802%2F11%2F20180211164303_tqlpj.thumb.700_0.jpg "Optional title")
```

**参考式**

```shell
![Alt text][id]
「id」是图片参考的名称，图片参考的定义方式则和连结参考一样：
[id]: url/to/image  "Optional title attribute"
```



### 2，示例

- 行内式

![赵丽颖1](../picture/zly.jpg)

![赵丽颖2](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1560405174093&di=c86d019653e9d7e8db08627fded4a2f5&imgtype=0&src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201802%2F11%2F20180211164303_tqlpj.thumb.700_0.jpg"Optionaltitle")



- 参考式

![赵丽颖][red]

[red]: ../picture/redzly.jpg  "redzly"

### 3，快捷键

> ctrl+shift+I