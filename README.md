# ReX团队开发规范

## 前言

此规范旨在规范ReX团队内部开发规范，提升内部和开源项目的代码可读性，便于团队成员协作及项目贡献者修改代码。请新人及贡献者仔细阅读并遵守相关规范。



## 代码编写相关规范

### 1）变量命名

​	a）公开变量：

​		公开变量应遵循 **小驼峰** 规则，即变量中每个单词首字母都要大写，如:

```java
public String userName;
public String password;
```

​	b)私有变量：

​		私有变量应遵循 **小驼峰** 规则，并在变量前插入一个下划线`_`，如:

``` java
private String _userName;
private String _password;
```

​	


## 版本控制系统相关规范

