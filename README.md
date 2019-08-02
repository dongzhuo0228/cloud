spring-cloud-consumer    ----  @EnableDiscoveryClient
spring-cloud-eureka      ----@EnableEurekaServer     这个作为注册机器 其本身不需要注册在uereka上
spring-cloud-producer     --- @EnableDiscoveryClient

其中eureka是注册机器   其余两个都要把服务注册在上面   充当中介的角色
其余两个都是客户端
