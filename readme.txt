服务一般是很容易就被杀死，如果出现内存不足的情况下，service可能就被杀掉，为了使程序不是那么容易被杀死，可以谢伟前台服务。
AIDLService：双向通信，一个APP通过AIDL可以访问另外一个APP的Service，但是项目还是不可以运行，在项目的配置中，
注册文件时报错异常，程序不可以运行。显示没有编写服务的类，但是项目中是已经编写了AIDLService的服务类，明天是解决问题所在。