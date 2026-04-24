# hcuhf (JitPack)

This repository is configured for JitPack.

## Publish

Create and push a git tag, then open:

`https://jitpack.io/#<your-github-username>/hcuhf/<tag>`

## Dependency

```gradle
dependencyResolutionManagement {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}

dependencies {
    implementation 'com.github.<your-github-username>:ModuleAPI:<tag>'
}
```
