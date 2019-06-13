# 代码区块

### 1，示例

- Java

```java
/**
 * <p>文件名称: GateMainApp.java</p>
 * <p>文件描述: </p>
 * <p>版权所有: 版权所有(C)2015-2017</p>
 * <p>公    司: 深圳市金证科技股份有限公司</p>
 * <p>内容摘要: </p>
 * <p>其他说明: </p>
 * <p>完成日期：2018年03月15日</p>
 *
 */
package com.szkingdom;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.cloud.client.circuitbreaker.EnableCircuitBreaker;
import org.springframework.cloud.client.discovery.EnableDiscoveryClient;
import org.springframework.cloud.netflix.hystrix.EnableHystrix;
import org.springframework.cloud.netflix.hystrix.dashboard.EnableHystrixDashboard;
import org.springframework.cloud.netflix.zuul.EnableZuulProxy;
import org.springframework.context.annotation.Bean;
import org.springframework.context.annotation.ComponentScan;

/**
 * 网关启动入口
 * @author yyh
 * @version 3.1.0 2018年03月15日
 * @see
 * @since jisp
 */
//@Profile(value = "dev")
@ComponentScan({"com.szkingdom"})
@EnableZuulProxy
@SpringBootApplication
@EnableDiscoveryClient
//@EnableHystrixDashboard
//@EnableCircuitBreaker
@EnableHystrix
@EnableCircuitBreaker
public class GateMainApp
{

    public static void main(String[] args) {
        SpringApplication.run(GateMainApp.class, args);
    }

}
```

- shell

```shell
#!/bin/bash
echo "Stopping msa"
pid=`ps -ef | grep jmsa-web-actuator-3.1.1-SNAPSHOT.jar | grep -v grep | awk '{print $2}'`
if [ -n "$pid" ]
then
   echo "kill -9 的pid:" $pid
   kill -9 $pid
fi

```

- html

```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <meta name="keywords" content="Editor.md, Markdown, Editor" />
        <title>Hello world!</title>
        <style type="text/css">
            body{font-size:14px;color:#444;font-family: "Microsoft Yahei", Tahoma, "Hiragino Sans GB", Arial;background:#fff;}
            ul{list-style: none;}
            img{border:none;vertical-align: middle;}
        </style>
    </head>
    <body>
        <h1 class="text-xxl">Hello world!</h1>
        <p class="text-green">Plain text</p>
    </body>
</html>

```



