# SkyHigh 16KB Doctor

A Gradle plugin that scans Android APK/AAB outputs for native `.so` libraries, checks ELF `p_align` values (16KB target), maps libraries back to owners (module or dependency), and produces machine- and human-friendly reports.

<img width="1472" height="704" alt="Image" src="https://github.com/user-attachments/assets/67afd550-931f-4ea1-8478-8b9c2abce572" />

[![Latest Version on Maven Central](https://img.shields.io/maven-central/v/io.github.sparrow007/skyhigh-16kb-doctor.svg?label=Maven%20Central)](https://search.maven.org/artifact/io.github.sparrow007/skyhigh-16kb-doctor)

## 🚀 Features

- **Automatic scanning** for 16KB page alignment
- **Easy integration** with Gradle
- **Detailed reports** for developers
- **Kotlin & Java support**


## 📦 Installation

Add the plugin to your `build.gradle.kts`:

In your Android application module (or app):

```kotlin
plugins {
  id("com.sparrow.skyhigh.16kb-doctor") version "1.0.0"
}
```

## 🛠 Usage

After applying the plugin, run:

```
./gradlew skyhighDoctorPlugin

```

## 🔁 Sync your project

After adding the dependency, click **"Sync Now"** in Android Studio or run the following command in your terminal to sync your project:

```sh
./gradlew build
```

## 📝 HTML Report

<img width="1884" height="278" alt="Image" src="https://github.com/user-attachments/assets/0558b9ca-7617-44f2-8e2e-10cf6408f69c" />

## 🤝 Contribution
We welcome contributions to the SkyHigh 16KB Doctor! Here are some ways you can help:

## 🐞 Report a Bug
If you find an issue, please open a new issue ticket on GitHub. Please provide as much detail as possible, including steps to reproduce the problem.


## Find this repository useful? ❤️
Support it by joining __[stargazers](https://github.com/sparrow007/skyhigh-16kb-doctor/stargazers)__ for this repository. :star: <br>
 And __[follow](https://github.com/sparrow007)__  me for next creation 🤩

## Thanks
Your feedback helps us improve the plugin.

## License
```xml
Copyright 2025 Sparrow007 (Ankit kumar)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
