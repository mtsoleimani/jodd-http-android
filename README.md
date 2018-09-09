# jodd-http-android

Port Jodd-Http to android (v5.0.4)



Jodd HTTP is tiny, raw HTTP client - and yet simple and convenient. It offers a simple way to send requests and read responses - so to please developers.

This repository represent of ported Jodd HTTP to Android. Some modifications has been performed to run in android.
To use this library you have to use Android Studio with Java 8. Please add the following lines to compile 
your application with java 8

```sh
compileOptions {
    sourceCompatibility JavaVersion.VERSION_1_8
    targetCompatibility JavaVersion.VERSION_1_8
}
```


In directory output, there is 2 jar files: jodd_http_android_vXXX.jar and javax_activation.jar
You need also to add javax_activation.jar to your project.

```sh
dependencies {
    api files('libs/jodd_http_android_vXXX.jar')
    api files('libs/javax_activation.jar')
}
```


### How to use
please refer to https://jodd.org/http/ for documentation and simple quick start


### TO DO

 - Android Studio project examples

