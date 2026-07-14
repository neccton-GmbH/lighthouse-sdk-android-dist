# Lighthouse SDK Android Dist

Public distribution repository for released Lighthouse Android SDK artifacts.

## Gradle

```kotlin
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
        maven(url = "https://raw.githubusercontent.com/neccton-GmbH/lighthouse-sdk-android-dist/main/maven")
    }
}
```

```kotlin
dependencies {
    implementation("ai.neccton:lighthouse-sdk:0.1.1")
}
```
