# 段落

### 1，要求

段落的**前后要有空行**，所谓的空行是指没有文字内容。若想在段内强制换行的方式是使用**两个以上空格加上回车**（引用中换行省略回车）

### 2，示例

- 效果

在[Docker Store](https://store.docker.com/)上有非常多的高质量的官方镜像，有可以直接拿来使用的服务类的镜像，如 nginx、redis、mongo、mysql、httpd、php、tomcat 等；也有一些方便开发、构建、运行各种语言应用的镜像，如 node、openjdk、python、ruby、golang 等。可以在其中寻找一个最符合我们最终目标的镜像为基础镜像进行定制。

如果没有找到对应服务的镜像，官方镜像中还提供了一些更为基础的操作系统镜像，如 ubuntu、debian、centos、fedora、alpine 等，这些操作系统的软件库为我们提供了更广阔的扩展空间。

除了选择现有镜像为基础镜像外，Docker 还存在一个特殊的镜像，名为`scratch`。这个镜像是虚拟的概念，并不实际存在，它表示一个空白的镜像。
