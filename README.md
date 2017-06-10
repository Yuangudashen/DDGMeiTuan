# MeiTuan App Write In latest React-Native(0.44.0)

Github：https://github.com/dudongge/DDGMeiTuan

简书：http://www.jianshu.com/p/42097aa798fa


##  screen shot for iOS

<img src="https://github.com/dudongge/DDGMeiTuan/blob/master/screenshot/iOS_0.png">

<img src="https://github.com/dudongge/DDGMeiTuan/blob/master/screenshot/iOS_1.png">

<img src="https://github.com/dudongge/DDGMeiTuan/blob/master/screenshot/iOS_2.png">

<img src="https://github.com/dudongge/DDGMeiTuan/blob/master/screenshot/iOS_3.png">
## screen shot for Android

<img src="https://github.com/dudongge/DDGMeiTuan/blob/master/screenshot/Android_0.png">

<img src="https://github.com/dudongge/DDGMeiTuan/blob/master/screenshot/Android_1.png">

<img src="https://github.com/dudongge/DDGMeiTuan/blob/master/screenshot/Android_2.png">

<img src="https://github.com/dudongge/DDGMeiTuan/blob/master/screenshot/Android_3.png">

## Setup

1. **Clone the repo**

```
$ git clone https://github.com/dudongge/DDGMeiTuan.git
$ cd DDGMeiTuan
```

2. **Install dependencies** (npm v3+):

```
$ npm install
```


3. **Running on iOS:**

```
$ react-native run-ios
```

## Troubleshooting

> Could not connect to development server

In a separate terminal window run:

```
$ react-native start
```

## Dependency

* [react-navigation](https://github.com/react-community/react-navigation)
* [react-native-scrollable-tab-view](https://github.com/skv-headless/react-native-scrollable-tab-view)

## Contact


## At last

If you like this project, please give me a star  :)


# 高仿美团客户端 React-Native版(0.44.0)

## 简介


这是一个用React-Native写的美团客户端。

使用了React-Native 0.44.0版本。遵循ES6语法。

主要实现了美团的四个一级页面（团购、附近、订单、我的），以及部分二级页面（团购详情、Web页面）。

所有功能都是用JavaScript写的，iOS和Android的代码复用率达到了100%（因为只写了一套代码）。

开发时所用的工具是webStrom. 安装破解汉化 http://www.jianshu.com/p/97bb2096c24c。

这个Demo的静态类型检查工具使用了Facebook的Flow。它让我写JavaScript的时候，更有安全感。个人觉得可以用两个字形容这个工具，那就是：灰常牛逼！

我试着让这个Demo的结构尽量接近实际项目，同时使用比较简单方式去实现功能。这样可以让刚接触ReactNative的人（比如我自己...）更够容易理解代码。

该项目没有使用Redux。因为个人觉得目前大部分的中小型App并不需要Redux。如果盲目的将Redux添加到项目中，并不能带来太多的益处。


App的页面跳转、TabBar、Navigation，全部通过[react-navigation](https://github.com/react-community/react-navigation)实现。这是一个非常牛逼的库，可以实现很多自定义的跳转功能。最早是通过[react-native-router-flux](https://github.com/aksonov/react-native-router-flux)实现跳转。在遇见react-navigation后，我果断放弃了react-native-router-flux。

App中很多页面都使用了同一个网络接口，这不是为了让代码更加简洁，因为接口有限😑 >.<

## 第三方依赖

* [react-navigation](https://github.com/react-community/react-navigation)
* [react-native-scrollable-tab-view](https://github.com/skv-headless/react-native-scrollable-tab-view)

## 安装

1. **Clone the repo**

```
$ git clone https://github.com/dudongge/DDGMeiTuan.git
$ cd DDGMeiTuan
```

2. **Install dependencies** (npm v3+)

```
$ npm install
```

3. **Running on iOS**

```
$ react-native run-ios
```

## 常见问题

> Could not connect to development server

打开新的terminal窗口，并执行:

```
$ react-native start
```



## 如果对您有帮助，开心的给个star吧
江南烟雨绕城郭，
白银盘里绕青螺。
天下儿女多才俊，
最是风流杜东阁
--目前就职于上海二三四五网络 希望和各路大神交流切磋。
Github：https://github.com/dudongge/DDGMeiTuan

