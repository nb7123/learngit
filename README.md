Baidu map sdk wrapped to android 'aar' library and deployed to maven central
====================================
[![Build Status](https://travis-ci.org/loopj/android-async-http.png?branch=master)](https://travis-ci.org/loopj/android-async-http)

Bai du map sdks wraped to android 'aar' library and deployed to maven central, based [Baidu map sdks](http://developer.baidu.com/map/).

#Version
mapapi: base,map,cloud,radar,search,util	3.6.0

location: 6.13

trace: 2.0.0

Changelog
---------
See http://developer.baidu.com/map/

Javadoc
-------
See http://developer.baidu.com/map/

Features
--------
See http://developer.baidu.com/map/

Examples
--------

See individual samples [here on Github](https://github.com/nb7123/BaiduMapSDK/tree/master/sample)  
To run Sample application, simply clone the repository and test with 'android studio'  

Maven
-----
You can now integrate this library in your project via Maven. There are available two kind of builds.

**releases, maven central**

Gradle
```groovy
repositories {
  maven {
    mavenCentral()
  }
}
dependencies {
	compile 'com.baidu.mapapi:base:3.6.0'
    compile 'com.baidu.mapapi:map:3.6.0'
    compile 'com.baidu.mapapi:cloud:3.6.0'
    compile 'com.baidu.mapapi:radar:3.6.0'
    compile 'com.baidu.mapapi:search:3.6.0'
    compile 'com.baidu.mapapi:util:3.6.0'
    compile 'com.baidu.mapapi:location:6.13'
}
```

**development snapshots**

https://oss.sonatype.org/content/repositories/snapshots/com/baidu/mapapi/

Gradle
```groovy
repositories {
  maven {
    url 'https://oss.sonatype.org/content/repositories/snapshots/'
  }
}
dependencies {
	compile 'com.baidu.mapapi:base:3.6.0-SNAPSHOT'
    compile 'com.baidu.mapapi:map:3.6.0-SNAPSHOT'
    compile 'com.baidu.mapapi:cloud:3.6.0-SNAPSHOT'
    compile 'com.baidu.mapapi:radar:3.6.0-SNAPSHOT'
    compile 'com.baidu.mapapi:search:3.6.0-SNAPSHOT'
    compile 'com.baidu.mapapi:util:3.6.0-SNAPSHOT'
    compile 'com.baidu.mapapi:location:6.13-SNAPSHOT'
}
```

Documentation, Features and Examples
------------------------------------
Full details and documentation can be found on the project page here:

http://developer.baidu.com/map/

