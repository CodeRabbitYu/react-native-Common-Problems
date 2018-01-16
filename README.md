
## react-native 开发常见问题

#### iOS
> 1、 在不修改`info.plist`文件之前，一定要用`https`的网络请求(如何修改请百度)；
> 
> 2、在使用定位，拍照，相机等权限的时候，也需要在`info.plist`中修改，可以参考[react-native-image-picker闪退的解决办法](https://www.jianshu.com/p/977bc5eea1b1)
>
>3、搜索框、长按等出来的菜单，做本地化处理后，可显示中文


#### Android
> 1、真机调试的时候，需要在`Dev Settings`里面修改`Debug server host & port for device`，将`本地IP + :8081`填入输入框；
>
> 2、真机调试的时候，如果无法通过摇一摇唤起开发菜单，可以通过终端运行`adb shell input keyevent 82`唤起；
>
> 3、真机调试的时候，小米、魅族要开启悬浮窗权限和关闭MIUI优化；

