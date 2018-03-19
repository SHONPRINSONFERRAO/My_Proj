# JUMIA DEALS APP

Jumia Deals Android App to Buy & Sell Everything 

## Getting Started

These instructions will get you a idea of project up and running on your local machine for development and deployment.

### Prerequisites

What things you need to install the software and how to install them

Android Studio

Android SDK

Java 8 Environment

### Installing

Please follow instructions provided by Android Studio with suitable SDK version

### Building App and Running

To build App

~~~
./gradlew build
~~~

To clean App
~~~
./gradlew clean
~~~

To Assemble or Build Debug App
~~~
./gradlew assembleDebug
~~~

To Assemble or Build Release(Signed) App
~~~
./gradlew assembleRelease
~~~

To Install Debug App
~~~
./gradlew installDebug
~~~

To Install Release App
~~~
./gradlew installRelease
~~~

To Uninstall Debug App
~~~
./gradlew uninstallDebug
~~~

To uninstall Release App
~~~
./gradlew uninstallRelease
~~~

### Docker Instructions

## Project Pre Requisites

Google SDK config json file
To be placed inside App folder(inside app)
~~~
google-services.json
~~~

Keystore properties file
To be placed inside Root folder(inside deals-android)
~~~
keystore.properties
~~~

Keystore file
To be placed inside Root folder(inside deals-android)
~~~
jumia_classifieds_deals.jks
~~~
