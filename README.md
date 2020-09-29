##### 此仓库为茶山刘项目部署仓库
 1. 部署流程： 每一次部署都要给 docker-compose.yml 命名
    
    命名格式为: docker-compose-2020-9020.yml
    
 2. 部署方式： 
 
    `docker-compose -f docker-compose-2020-9-26.yml  --env-file embrace_config.yml up -d`

##### 我们目前使用的镜像示例如下，镜像也要打标签：
 1. rabbitmq:3.8.8-management
 2. postgres:13.0
 3. redis:6.0.8
 4. wangyuefei/icm-scripts-scheduler:0.1 
