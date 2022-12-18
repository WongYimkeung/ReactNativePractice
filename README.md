# ReactNativePractice

一开始对于 ReactNative 实在是不感冒，可能是由于写习惯了强类型语言 Java 所以对于弱类型语言 Javascript 实在是厌烦。
可是最近经过 QML 的洗礼，感慨 Javascript 的强大以及跨端的同时，对于 ReactNavive 竟然提起了兴趣来，趁着这股上头的劲，做下实践和创建下这个仓库。

（是的，没有看错，因为写 QT 的 QML 所以对于 Javascript 产生了兴趣再到对之前用过的 ReactNative 上了头，就是这么的神奇。QML 中也支持使用 Javascript 这我真的没想到 doge）

## ReactNative 介绍

[React Native 官方网站](https://reactnative.dev/)

[React Native 中文网站](https://www.reactnative.cn/)

[React Native 源码](https://github.com/facebook/react-native)

## 开发环境配置

- Java 开发环境

1. 安装 [Java SDK](https://www.oracle.com/java/technologies/downloads/)

2. 配置 Java 环境变量

    JAVA_HOME = ***your_java_sdk_path***

    PATH = %PATH%;%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;

3. 验证 Java 开发环境是否配置成功

    java -version / javac -version

- Android 开发环境

1. [安装 Android Studio](https://developer.android.com/studio)

2. 配置 Android 环境变量

    > Toos -> SDK Manager -> Appearance Behavior -> System Settings -> Android SDK

    ANDROID_HOME = ***your_android_sdk_path***

    PATH = %PATH%;%ANDROID_HOME%\tools;%ANDROID_HOME%\tools\bin;%ANDROID_HOME%\platform-tools;

3. 验证 Android 开发环境是否配置成功

    adb devices

- React Native 开发环境

1. 安装 [Node.js](https://nodejs.org/en/)
    
2. 配置淘宝镜像源 : npm config set registry https://registry.npm.taobao.org

3. 安装 Yarn : npm install -g yarn

4. 安装 React Native 脚手架 : npm install -g react-native-cli

5. 验证 React Native 开发环境是否配置成功

    node --version

    npm -version

    yarn -version

- 创建项目

    react-native init ***your_project_name***

## 常用第三方库

以下第三方组件都可以在 Github 上面找到使用文档！

- [react-navigation](https://github.com/react-navigation/react-navigation) : 导航组件

- [react-native-webview](https://github.com/react-native-webview/react-native-webview) : WebView 组件

- [react-native-async-storage](https://github.com/react-native-async-storage/async-storage) : 持久化存储工具

- ~~[react-native-camera deprecated](https://github.com/react-native-camera/react-native-camera) : 摄像头~~

- [react-native-vision-camera](https://github.com/mrousavy/react-native-vision-camera) : 摄像头

- [react-native-image-picker](https://github.com/react-native-image-picker/react-native-image-picker) : 图片选择组件

- [react-native-image-crop-picker](https://github.com/ivpusic/react-native-image-crop-picker) : 图片裁剪组件

- [react-native-svg](https://github.com/software-mansion/react-native-svg) : SVG 组件

- [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) : 矢量图标库

- [react-native-linear-gradient](https://github.com/react-native-linear-gradient/react-native-linear-gradient) : 线性渐变组件

- [lottie-react-native](https://github.com/lottie-react-native/lottie-react-native) : JSON 格式动画组件

- [react-native-animatable](https://github.com/oblador/react-native-animatable) : 动画组件库

- [react-native-paper](https://github.com/callstack/react-native-paper) : Material Design UI 组件库

- [react-native-picker](https://github.com/beefe/react-native-picker) : 下拉框组件

- [react-native-swiper](https://github.com/leecade/react-native-swiper) : 滑动展示轮播效果组件

- [react-native-modal](https://github.com/react-native-modal/react-native-modal) : Modal 组件

- [react-native-gesture-handler](https://github.com/software-mansion/react-native-gesture-handler) : 手势处理组件

- [react-native-gifted-chat](https://github.com/FaridSafi/react-native-gifted-chat) : 聊天功能组件

## 项目结构说明

## 学习资料参考

- [React 入门应该是这样的](https://www.bilibili.com/video/BV1be411w7iF/)

- [React Native 入门到实战](https://www.bilibili.com/video/BV1Pt4y1n7bD/)

- [awesome-react-native](https://github.com/jondot/awesome-react-native) : react-native学习参考，包括继承和好用react native库推荐