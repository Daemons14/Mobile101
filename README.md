# Volley 101 : Reliable and Fast Networking for Android

Volley is a library that makes networking for most Android apps easier, reliable and  most importantly, faster. Compare to Asynctask, volley get and post data faster.


# How to use

The library can now be referenced in an Android application project in the app/build.gradle as follows:

```
dependencies {
    compile 'com.android:volley:1.0.+'
}
```

Make sure to also reference the local Maven repository in your root build.gradle as shown here:

```

buildscript {
    repositories {
        mavenCentral()
    }
    dependencies {
        classpath 'com.android.tools.build:gradle:0.9.+'
    }
}

allprojects {
    repositories {
        mavenCentral()
        mavenLocal() // When you forget this, the library will not be found
    }
}

```

#Other Sources









