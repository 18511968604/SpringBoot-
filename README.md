# Spring boot入门

### Spring Boot 简介





### 环境准备

1. Maven设置
2. IDEA设置

### Spring Boot HelloWorld

 一个功能： 通过浏览器访问/hello路径，返回“hello world 字符串”  


1.  创建一个Maven项目 （Jar）
2. 导入SpringBoot依赖 
   1. ```text
          <parent>
              <groupId>org.springframework.boot</groupId>
              <artifactId>spring-boot-starter-parent</artifactId>
              <version>2.2.1.RELEASE</version>
          </parent>

          <dependencies>
              <dependency>
                  <groupId>org.springframework.boot</groupId>
                  <artifactId>spring-boot-starter-web</artifactId>
              </dependency>
          </dependencies>
      ```





![](.gitbook/assets/image%20%284%29.png)









