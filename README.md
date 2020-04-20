# Vivo_unlock
Vivo Y51系列机型解锁BL锁，**仅仅适用于Vivo Android6.0以前手机版本，其他版本Vivo手机，无效。**
# 使用方法
## 准备工作
1.下载全部文件
2.手机进入献祭模式（Fastboot）
3.连接电脑，并确保Fastboot驱动安装，即：电脑成功连接手机。

## 解锁过程
1.打开fastboot.exe文件
2.管理员许可
3.解锁成功

## 解锁原理
Vivo早期版本fastboot是可以解锁的，只需要:
```
fastboot bbk unlock vivo
```

# Worning
该fastboot仅在Y51系列测试通过，其他手机未测试。
**Vivo手机解锁后，控制台可能还是显示device unlock fail，但是是成功解锁的。开机并没有提示（Device is unlock）。但是，解锁后，可刷入Twrp等第三方Recovery。**
