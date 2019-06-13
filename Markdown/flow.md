# 流程图

### 1，定义格式

```shell
​```flow
# 此处使用=>定义步骤
st=>start: 用户登陆
op=>operation: 登陆操作
cond=>condition: 登陆成功 Yes or No?
e=>end: 进入后台
# ->定义流程
st->op->cond
cond(yes)->e
cond(no)->op
​```
```

### 2，示例

- 效果

  ```flow
  st=>start: 用户登陆
  op=>operation: 登陆操作
  cond=>condition: 登陆成功 Yes or No?
  sss=>operation: 跳转首页
  e=>end: 进入后台
  
  st->op->cond
  cond(yes)->sss
  sss->e
  cond(no)->op
  ```

  

