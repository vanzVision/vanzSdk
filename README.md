# vanzSdk
智能结算台sdk包

工程build.gradle
```Java

allprojects {
    repositories {
        ...
        maven { url "https://github.com/vanzVision/vanzSdk/raw/master" }
    }
}
```

app build.gradle
```Java
dependencies{
      compile('com.vanz:vanzSdk:1.0.8')
}
```
