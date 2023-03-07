## application.properties中jdbc配置

```
spring.datasource.platform=postgresql 
db.num=1
db.url.0=jdbc:postgresql://127.0.0.1:5432/nacos_config?reWriteBatchedInserts=true&characterEncoding=utf8
db.user.0=nacos
db.password.0=nacos
db.pool.config.driverClassName=org.postgresql.Driver