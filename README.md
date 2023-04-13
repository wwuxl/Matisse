由于原作者更新，对https://github.com/zhihu/Matisse 项目切换顶部选项显示空白问题进行修复


Gradle:

```groovy
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}

dependencies {
    implementation 'com.github.wwuxl:Matisse:1.0.0'
}
```