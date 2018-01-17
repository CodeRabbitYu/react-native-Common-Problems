
## react-native 开发常见问题

#### JS
> RN开发使用的是JavaScript，不管是ES5，ES6, TypeScript，只要是JS的语法，RN都能用，如果遇到JS问题，请直接百度。
> 

#### 通用
> 1、RN里面真的没有好用的下拉刷新和上拉加载组件，都是用`ScrollView`，`FlatList`，`SectionList`，`ListView`提供的效果；

#### iOS
> 1、 在不修改`info.plist`文件之前，一定要用`https`的网络请求(如何修改请百度)；
> 
> 2、在使用定位，拍照，相机等权限的时候，也需要在`info.plist`中修改，可以参考[react-native-image-picker闪退的解决办法](https://www.jianshu.com/p/977bc5eea1b1)；
>
> 3、搜索框、长按等出来的菜单，做本地化处理后，可显示中文；
>

#### Android
> 1、真机调试的时候，需要在`Dev Settings`里面修改`Debug server host & port for device`，将`本地IP + :8081`填入输入框；
>
> 2、真机调试的时候，如果无法通过摇一摇唤起开发菜单，可以通过终端运行`adb shell input keyevent 82`唤起；
>
> 3、真机调试的时候，小米、魅族要开启悬浮窗权限和关闭MIUI优化；

#### 版本问题
##### 已知
> 1、0.52版本`react-native-vector-icons`正常安装后不能使用。
> 解决方式：执行`rm ./node_modules/react-native/local-cli/core/__fixtures__/files/package.json`。
> 参考[https://github.com/oblador/react-native-vector-icons/issues/626](https://github.com/oblador/react-native-vector-icons/issues/626)。

#### 布局

> 虽然RN使用的是精简版Flex，但Flex有用的绝大多数属性都是可以使用的，如果遇到布局问题，请查看阮一峰的教程。
####[Flex 布局教程](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html?utm_source=tuicool)
> ##### 稍后会将RN可以使用的Flex布局整理出来。
> 欢迎提PR
> 


