# vanzSdk
智能结算台sdk包

工程build.gradle
```Java

allprojects {
    repositories {
        ...
        maven { url "https://github.com/vanzVision/vanzSdk/raw/master" }
        maven { url 'http://raw.github.com/saki4510t/libcommon/master/repository/' }
        maven { url 'https://jitpack.io' }
    }
}
```

app build.gradle
```Java
dependencies{
      compile('com.vanz:vanzSdk:1.0.18')
}
```
## 2019.03.18
### 重点更新
* 修改设备灯常亮
* 修改物品放空时继续解析的问题