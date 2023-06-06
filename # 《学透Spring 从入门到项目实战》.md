# 《学透Spring 从入门到项目实战》

书籍：学透Spring 从入门到项目实战

作者: 丁雪丰

出版社: 人民邮电出版社

出版时间: 2023年2月

## 第一部分 Spring 入门

### 第一章 初识 Spring

本章内容

####  Spring 发展历史概述

- Java平台包括J2ME、J2SE和J2EE（现称Java ME、Java SE和Java EE）。
- Spring Framework是解决J2EE开发问题的解决方案，由Rod Johnson提出并于2004年发布1.0版本。
- Spring Framework不是与J2EE对立，而是为其提供补充，简化了J2EE应用的开发。
- 在国内，有人翻译并推广了Spring Framework，对其在国内的发展起到了推动作用。
- Spring Framework具有模块化设计，用户可以按需引入所需模块。
- Spring Boot解决了模块依赖的问题，并提供了强大的自动配置和面向生产的能力。
- Spring Boot成为了应用开发的重要框架。
- Spring Cloud提供了对云原生Java应用的支持。
- Spring这个名字不再仅指Spring Framework，而是指整个Spring家族。

#### Spring 家族主要成员介绍

##### Spring Framework
>功能丰富
>- 核心的依赖注入、AOP、资源管理
>- 完善的数据访问能力，事务管理、ORM框架支持
>- Spring MVC 代替 Struts，成为Java Web主流框架
>- Spring Framework 5响应式Web框架Spring WebFlux
>- 其他实用功能：调度任务支持、缓存抽象等实用功能

##### Spring Boot
>Spring Boot是一种用于开发生产级Spring应用的工具，它可以降低开发的门槛，减少配置量，并提供了健康检查、监控、度量指标和外化配置等生产所需的功能。它的起步依赖很好地解决了Spring应用的依赖管理问题，而自动配置功能可以根据条件自动进行配置，甚至可以做到零配置。Spring Boot的目的是让开发者专注于业务逻辑，而不必担心底层框架的细节。

##### Spring Cloud
>为了简化分布式系统的开发，Spring Cloud应运而生。Spring Cloud构建在Spring Boot提供的各种功能之上，通过一系列模块实现了服务发现、配置管理、服务路由、服务熔断、链路追踪等具体的功能。早期的Spring Cloud大量借鉴并引入了Netflix的最佳实践，后来也出现了基于流行开源设施的模块，如Spring Cloud Zookeeper、Spring Cloud Consul等。无论是大公司还是小公司，都可以使用Spring Cloud来快速搭建高可靠的分布式系统。

##### Spring Data

>Spring Data和Spring Cloud一样，包含许多子模块，包括对JDBC增强功能、JPA支持、各种类型的NoSQL支持以及对REST资源的支持。尽管底层数据库种类繁多，Spring Data仍然在其之上提供了统一的抽象，例如仓库（Repository）和模板（Template）。Spring Data确保了无论是使用RDBMS、Redis还是MongoDB等数据库，都具有相似的编程模型。

####  编写一个简单的 Spring 程序

####  全书实战案例概述

### 第二章 Spring Framework 中的loC 容器

### 第三章 Spring Framework 中的AOP