来自https://github.com/xiaour/SpringBootDemo


###  SpringBootDemo
本代码集成了SpringBoot+MyBatis+Redis+MySql。    

spring-boot-starter-parent版本1.5.2.RELEASE

```sql
-- ----------------------------
-- Table structure for `user_info`
-- ----------------------------
DROP TABLE IF EXISTS `user_info`;
CREATE TABLE `user_info` (
  `id` int(8) NOT NULL AUTO_INCREMENT,
  `name` varchar(20) NOT NULL,
  `age` int(2) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;

-- ----------------------------
-- Records of user_info
-- ----------------------------
INSERT INTO `user_info` VALUES ('1', 'xiaour', '18');
```

