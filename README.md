# mybatis-generator-maven-demo
mybatis generator quick demo for forgetful people,好久不用mybatis,如果要快速上手，深得mybatis最佳实践，[jpetstore](https://github.com/mybatis/jpetstore-6)自然是最好的例子.如果更懒，就直接连接到数据库表，生成代码改改用吧


## 快速开始

1. 修改 src/main/resources/generatorConfig.xml
2. mvn mybatis-generator:generate


## JPA 更好的选择

使用Generator生成的代码，越来越像JPA/Hibernate的代码，但比JPA的要乱，在保证半自动化时，又要变懒，Dzone 2015 报告就不足为奇


![dzone_persistence](https://blogs.oracle.com/theaquarium/resource/dzone_persistence.png)
