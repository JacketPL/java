**春风如贵客，一到便繁华。各位看官<font color= red>点赞</font>再看，养成好习惯(●´∀｀●)**

> **gitee上已经开源 [https://gitee.com/Li-Ren/blog](https://gitee.com/Li-Ren/blog) 里面有我的<font color= red>联系方式和一线大厂面试点脑图，</font>欢迎Star和PR你认为重要的知识点。**

**之后还会推出JAVA面试系列文章，敬请关注！**

**<font color= red>按照技术模块：</font>**多线程**、微服务、<font color= red>JVM、Redis、消息队列、SQL相关的面试题。不要走开，稍后更精彩！</font>**

------

**[1、什么是微服务？（暗藏杀机）](https://blog.csdn.net/qq_26465035/article/details/103338710)**

**[2、什么是微服务扩展性和高可用-可扩展性、高可用性和性能](https://jjlu521016.github.io/2019/05/14/翻译/微服务/微服务扩展性和高可用-章节1.html#more)** 

**3、架构师在微服务架构中的角色是什么？**

>​	决定整个软件系统的布局。 帮助确定组件的分区。 为开发微服务的团队提供某些工具和技术的建议。 提供技术治理，以便技术开发团队遵循微服务原则。

**[4、什么是 CI 持续集成](https://www.jianshu.com/p/ef0a86e29707)**

**5、什么是Canary Releasing？说说你在项目中的应用**

>​	一种降低在生产中引入新软件版本的风险的技术，通过将变更缓慢地推广到一小部分用户，然后将其发布到整个基础架构。浅谈下你在项目中引进的新技术之类的。但切记不可多言。

**[6、springboot实现拦截器](https://blog.csdn.net/aiyongbo123456/article/details/85316195)**

**[7、如何使用Spring Boot实现异常处理?](https://blog.csdn.net/u010657094/article/details/78993929)**

**[8、Web，RESTful API在微服务中的作用是什么？](https://www.jianshu.com/p/c8ba0704fa21?from=groupmessage)**

**[9、什么是消费者驱动的合同（CDC）？](http://www.uml.org.cn/wfw/201907043.asp)**

**[10、从微服务到微服务测试](https://blog.csdn.net/wangxindong11/article/details/97253576)**

**[11、什么是OAuth？](https://www.jianshu.com/p/de560d398c91)**

**[12、什么是客户证书？](https://www.2cto.com/kf/201811/787936.html)**

**[13、什么是有界上下文](https://www.jdon.com/50864)**

**[14、微服务项目的设计要点](https://www.jianshu.com/p/d64cb97088ed)**

**15、Spring Cloud解决了哪些问题？**

> - 与分布式系统相关的复杂性 – 包括网络问题，延迟开销，带宽问题，安全问题。
> - 处理服务发现的能力 – 服务发现允许集群中的进程和服务找到彼此并进行通信。
> - 解决冗余问题 – 冗余问题经常发生在分布式系统中。
> - 负载平衡 – 改进跨多个计算资源（例如计算机集群，网络链接，中央处理单元）的工作负载分布。
> - 减少性能问题 – 减少因各种操作开销导致的性能问题。

**[16、什么是Spring Cloud？](https://blog.csdn.net/qq32933432/article/details/89918264)**

**[17、什么是Spring引导的执行器？](https://blog.csdn.net/leilei107/article/details/93855239)**

**[18、微服务架构如何进行解耦？](https://blog.csdn.net/belalds/article/details/85235935)**

**[19、为什么需要域驱动设计(DDD)?](https://www.jianshu.com/p/a7dc57dfd347)**

**[20、微服务之间是如何独立通讯的?](https://blog.csdn.net/weixin_43375482/article/details/99305084)**

**[21、Spring 和 SpringBoot 有什么不同?](https://www.jianshu.com/p/ffe5ebe17c3a)**

**[22、SpringBoot starter 作用在什么地方?](https://blog.csdn.net/songzehao/article/details/100837463)**

**23、怎么禁用某些自动配置特性？**

>// 方案1，下面的代码段是使 DataSourceAutoConfiguration 无效：
>@EnableAutoConfiguration(exclude = DataSourceAutoConfiguration.class)
>public class MyConfiguration {}
>// 方案2
>@SpringBootApplication(exclude = DataSourceAutoConfiguration.class)
>public class MyConfiguration { }
>// 方案3，// 在配置文件中配置一种通过配置文件yml或者properties，内设置 

**[24、SpringBoot 的自动化配置](https://www.jianshu.com/p/e0b4437547f5)**

**25、当 bean 存在的时候怎么置后执行自动配置？**

>​	为了当 bean 已存在的时候通知自动配置类置后执行，我们可以使用 *@ConditionalOnMissingBean* 注解。这个注解中最值得注意的属性是：
>
>- value：被检查的 beans 的类型
>- name：被检查的 beans 的名字
>
>当将 *@Bean* 修饰到方法时，目标类型默认为方法的返回类型：

```java
@Configuration
public class CustomConfiguration {
    @Bean
    @ConditionalOnMissingBean
    public CustomService service() { ... }
}
```

**26、怎么使用 SpringBoot 去执行命令行程序？**

> ​	像其他 Java 程序一样，一个 SpringBoot 命令行程序必须要有一个 *main* 方法。这个方法作为一个入口点，通过调用 *SpringApplication#run* 方法来驱动程序执行：  

```java
@SpringBootApplication
public class MySpringBootApplication {
    public static void main(String[] args) {
        SpringApplication.run(MySpringBootApplication.class);
    }
}
```

**27、SpringBoot 支持松绑定代表什么？**

>​	SpringBoot中的松绑定适用于配置属性的类型安全绑定。使用松绑定，环境属性的键不需要与属性名完全匹配。这样就可以用驼峰式、短横线式、蛇形式或者下划线分割来命名 
>
>**表示驼峰式、下划线(_)、短横线(-)**
>
>标准方式
>person.firstName
>
>方式一：大写用-
>person.first-name
>
>方式二：大写用_
>person.first_name
>
>三种方式，都可以使用
>推荐，属性书写方式
>PERSON_FIRST_NAME

[28、SpringBoot DevTools 的用途是什么?](https://www.jianshu.com/p/99f17c7e12f5)

**29、Java中springboot常用的starter有哪些**

> - spring-boot-starter-web 嵌入tomcat和web开发需要servlet与jsp支持 
> - spring-boot-starter-data-jpa 数据库支持 
> - spring-boot-starter-data-redis redis数据库支持 
> - spring-boot-starter-data-solr solr支持 
> - mybatis-spring-boot-starter 第三方的mybatis集成starter

**30、Spring Initializr 是创建 Spring Boot Projects 的唯一方法吗？**

> - 第一种方法是 start.spring.io  
>
> - 在 Idea 中，使用文件 - 新建 Maven 项目来创建一个新项目
>
>   1.添加依赖项。
>
>   2.添加 maven 插件。
>
>   3.添加 Spring Boot 应用程序类。
>

**[31、为什么我们需要 spring-boot-maven-plugin?](https://www.cnblogs.com/acm-bingzi/p/mavenSpringBootPlugin.html)**

**[32、什么是 Spring Data?](https://blog.csdn.net/qq_32328959/article/details/88293914)**

**[33、我们能否在 spring-boot-starter-web 中用 jetty 代替 tomcat？](https://blog.csdn.net/hanchao5272/article/details/99649252)**

**[34、如何使用 Spring Boot 生成一个 WAR 文件?](https://blog.csdn.net/yalishadaa/article/details/70037846)**

**35、RequestMapping 和 GetMapping 的不同之处在哪里？**

> Spring4.3中引进了｛@GetMapping、@PostMapping、@PutMapping、@DeleteMapping、@PatchMapping｝，来帮助简化常用的HTTP方法的映射，并更好地表达被注解方法的语义。
>
> 以@GetMapping为例，Spring官方文档说：
> @GetMapping是一个组合注解，是@RequestMapping(method = RequestMethod.GET)的缩写。该注解将HTTP Get 映射到 特定的处理方法上。

**[36、可以配置 application.propertierde 的完整的属性列表在哪里可以找到?](https://docs.spring.io/spring-boot/docs/current/reference/html/appendix-application-properties.html)**

**37、JPA 和 Hibernate 有哪些区别？**

> - Hibernate是JPA规范的一个具体实现
> - hibernate有JPA没有的特性 
> - hibernate 的效率更快
> - JPA 有更好的移植性，通用性

**38、Spring Boot 的核心注解是**

> @SpringBootApplication 

**39、开启 Spring Boot 特性有哪几种方式？**

```java
1)继承spring-boot-starter-parent项目
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>2.2.1.RELEASE</version>
        <type>pom</type>
    </dependency>
2)导入spring-boot-dependencies项目依赖
```

**40、Spring Boot 需要独立的容器运行吗？**

> 可以不需要，内置了 Tomcat/Jetty 等容器。  

**[41、Spring Boot 的配置文件有哪几种格式？它们有什么区别？](https://blog.csdn.net/huofuman960209/article/details/93603970)**

**[42、SpringBoot 目录结构](https://blog.csdn.net/little_skeleton/article/details/80922725)**

**[43、Value注解读取方式有哪几种？](https://blog.csdn.net/hunan961/article/details/79206291)**

**[44、Spring Boot2  支持哪些日志框架?推荐和默认的日志框架是哪个?](https://blog.csdn.net/vi_young_95/article/details/86310832)**

**[45、保护 Spring Boot 应用有哪些方法？](https://www.cnblogs.com/javastack/p/9638563.html)**

**[46、Spring Boot 如何定义多套不同环境配置?](https://www.jianshu.com/p/e721eaeb8b44)**

**[47、spring boot bean作用域有哪些](https://blog.csdn.net/hbtj_1216/article/details/86383247)**

**[48、Spring为什么默认bean为单例？](https://www.jianshu.com/p/a298c8ea9e76)**

**[49、什么是JavaConfig？](https://blog.csdn.net/qq_40223688/article/details/102388080)**

**[50、Spring Boot中的监视器是什么?](https://www.jianshu.com/p/8bfac9289c7e)**





