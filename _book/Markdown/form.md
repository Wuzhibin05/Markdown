# 表格

### 1，定义格式

**格式一**： 使用`|`和`-`来组装表格。

​                冒号在右边代表居右显示；两边都有代表居中显示；默认居左显示。

​                标题自动加黑。

```shell
| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机      | $1600   |   5     |
| 手机        |   $12   |   12   |
| 管线        |    $1    |  234  |

```

**格式二：**左右两边不加`|`

```shell
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

**格式三：**混合模式

```shell
| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
```



### 2，示例

- 格式一

| 项目   |  价格 | 数量 |
| ------ | ----: | :--: |
| 计算机 | $1600 |  5   |
| 手机   |   $12 |  12  |
| 管线   |    $1 | 234  |

- 格式二（默认居左）

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

- 格式三

| Left-Aligned         |  Center Aligned   | Right Aligned |
| :------------------- | :---------------: | ------------: |
| **col 3 is**         | `some wordy text` |         $1600 |
| *col 2 is*           |     centered      |           $12 |
| <u>zebra stripes</u> |     are neat      |            $1 |

### 3，快捷键

> ctrl + T

