# The Ghettoest Maven Repository

This is just disgusting.

## How to consume me

1. Add the following to your root `build.gradle` file:

    ```
    allprojects {
        repositories {
            ...

            maven { url "https://raw.githubusercontent.com/julo15/ghetto-repo/master" }
        }
    }
    ```

2. Add the following to your app `build.gradle` file:

    ```
    dependencies {
        ...

        compile 'com.placed.client:android-persistent-sdk:1.20'
    }
    ```

Testing a checkin
Another checkin
