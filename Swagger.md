# Swagger

## 简介：

Swagger是最流行的API开发工具，它遵循OpenAPI Specification(OpenAPI规范，也简称OAS)，Swagger可以贯穿整个API生态，如API的设计，编写API文档，测试和部署。Swagger是一个规范和完整的框架，用于生成、描述、调用的和可视化的RESTful风格的Web服务，目标是使客户端和文件系统作为服务器以同样的速度来更新文件的方法，参数和模型紧密集成到i服务器。swagger是一款可以根据resultful风格生成的生成的接口开发文档，并且支持做测试的一款中间软件

Swagger是一种通用的，和变成语言无关的API描述规范。

## 应用场景：

- 如果你的RESTful API接口都开发完成了，你可以用Sagger-editor来编写API文档（yaml文档或者json文档），然后通过Swagger-ui来渲染文件，以非常美观的形势将你的API文档，展示给你的团队或者客户。
- 如果你是RESTful API还未开始，也可以使用Swagger，来设计和规范你的API，以Annotation（注解）的方式给你的源代码添加额外的数据，这样，Swagger就可以检测到这些数据，自动生成对应的API文档。

对后端开发人员来讲：

- 不用再手写WIKI接口并大量的参数，避免手写错误
- 对代码侵入性低，采用注解的方式，开发简单
- 方法参数名修改、增加、减少都可以直接生效、不用手动修改
- 缺点：增加开发成本，写接口还需要写一套参数配置

对于前端开发来说：

- 后端只需要定义好接口，会自动生成文档，接口功能，参数一目了然
- 联调方便，如果出问题，直接测试接口，实时检查参数和返回值，就可以快速定位是前端还是后端的问题

对于测试：

- 对于某些没有前端界面UI的功能，可以用它来测试接口
- 操作简单，不用了解具体代码的就可以操作

## 搭建Swagger

### 引入swagger的依赖

```xml
<!--引入swagger-->
<dependency>
    <groupId>io.springfox</groupId>
    <artifactId>springfox-swagger2</artifactId>
    <version>2.7.0</version>
</dependency>
<dependency>
    <groupId>io.springfox</groupId>
    <artifactId>springfox-swagger-ui</artifactId>
    <version>2.7.0</version>
</dependency>
```

### SpringBoot整合swagger

```java
@Configuration

```



