# RuLong-Socket

[View On GitHub](https://github.com/cjango/RuLong-Socket)

## 1.安装
```
$ composer require "rulong/laravel-socket:~0.1.0"
```

## 2.配置
```
$ php artisan vendor:publish --provider=" RuLong\Socket\ServiceProvider"
```

## 3.启动
--d 为deamon模式
```
$ php artisan workman start {--d}
```

## 4.停止
只有deamon模式下可用
```
$ php artisan workman stop
```

## 5.其他命令
重启 restart

平滑重启 reload

查看状态 status

查看链接 connections
