# mybatis-generator

由于在加入自定义插件时要手动引入jar包很不科学，所以放弃使用maven插件生成代码，改用main方法生成代码。
注意用main方法生成代码时，配置文件里的targetProject要是绝对路径。