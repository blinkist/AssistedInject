[<img src="https://jitpack.io/v/blinkist/AssistedInject.svg?style=flat-square">](https://jitpack.io/#blinkist/AssistedInject)

# Assisted Injection for Dagger 2 Shaded

This is a fork on [AssistedInject](https://github.com/square/AssistedInject) 
that points to [Dagger 2 Shaded](https://github.com/blinkist/dagger2-shaded) 
and understands the "new" annotations (`@Inject2`, `@Module2`, etc), so they can work together.

If you're using Dagger 2 Shaded and want to work with AssistedInject, just add this to your build:

```groovy
repositories {
  maven { url "https://jitpack.io" }
}

dependencies {
  implementation 'com.github.blinkist.AssistedInject:assisted-inject-annotations-dagger2:0.5.0-dagger2-shaded-friendly'
  kapt 'com.github.blinkist.AssistedInject:assisted-inject-processor-dagger2:0.5.0-dagger2-shaded-friendly'
}
```
