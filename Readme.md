# wJa环境
jdk 1.8
# 靶场测试环境
本地mysql开启   3306端口
user：root
pass：root
创建shoot数据库
执行如下sql：
```SQL
USE `shoot`;
CREATE TABLE IF NOT EXISTS `users`(
   `id` INT UNSIGNED AUTO_INCREMENT,
   `username` VARCHAR(255) NOT NULL,
   `password` VARCHAR(255) NOT NULL,
   PRIMARY KEY (`id`)
)ENGINE=InnoDB DEFAULT CHARSET=utf8;
INSERT INTO `users` VALUES (1, 'admin', 'admin123');
INSERT INTO `users` VALUES (2, 'joychou', 'joychou123');
```

# Issus

希望大家能够提出宝贵的建议，如果程序出现一些问题能够尽早的反馈给我，我会在两到三天时间进行修复和解答，感谢大家的支持。

视频观看地址：https://www.bilibili.com/video/BV19m4y1Q75X/

# 更新历史

2022.1.3:增加获取方法参数个数，可以有效对接口所有参数进行测试