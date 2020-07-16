# Laravel Package Maker

快速创建基于 laravel 组件包的工具

本工具参考：[overtrue/package-builder](https://packagist.org/packages/overtrue/package-builder)

# 安装方式


```shell

$ composer global require leeprince/laravel-package-maker

或者指定版本
$ composer global require leeprince/laravel-package-maker:dev-master

```

# 命令目录

```shell
 $ laravel-package-Maker
```

## 创建项目的命令

```
laravel-package-maker build [项目名 => name/com]
```

## 如下是实例

例如:
```shell
laravel-package-maker build foo/bar

Name of package (example: foo/bar): foo/bar
Namespace of package [Foo\Bar]:
Description of package:
Author name of package [leeprince]:
Author email of package [leeprince@foxmail.com]:
License of package [MIT]:
laravel service provider name : FooServiceProvider
Package foo/bar created in: ./foo/bar
```
