#时间：2020-02-25 08:29
# 作者：maxl   
# 工具和版本

    IntelliJIdea2019.2   

    8-Lambdas, type annotations etc.

    Maven: idea自带  Bundled(Maven 3) ignored by Maven 3+

    jdk1.8

    spring-boot 2.2.4
# 模块
    消费者：gateway-consumer: http://localhost:8001/hello/小明
    
    注册中心：gateway-eurea:    http://localhost:8375/
    
    生产者：gateway-producer: http://localhost:8000/hello?name=小明
    
    网关： gateway-gateway: 网关调用：http://localhost:8080/gateway/hello/小明
                           负载均衡：http://localhost:8080/gateway/ribbon 
            
    









