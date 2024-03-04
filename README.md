# Android Architecture

This is an Android starter project with MVVM architecture which you can use to bootstrap your application.
## Config

| SDK               | Version |
| ----------------- |---------|
| Min Sdk           | 23      |
| Compile Sdk       | 33      |
| Target Sdk        | 33      |

#### Kotlin & Gradle Versions

**1.** Gradle distributionUrl inside **gradle-wrapper.properties**
```
distributionUrl=https\://services.gradle.org/distributions/gradle-7.2-bin.zip
```

**2.** Kotlin version inside project level **build.gradle** plugins
```
id 'org.jetbrains.kotlin.android' version '1.8.0' apply false
```

## SDKs

**1. Dagger Hilt**
```
implementation "com.google.dagger:hilt-android:2.44"
kapt "com.google.dagger:hilt-compiler:2.44"
```

**2. Retrofit & OkHttp**
```
implementation 'com.squareup.retrofit2:retrofit:2.9.0'
implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
implementation 'com.squareup.okhttp3:logging-interceptor:4.10.0'
```