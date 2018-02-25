[![Kotlin](https://img.shields.io/badge/kotlin-1.2.21-blue.svg)](http://kotlinlang.org)  [![Maven Central](https://img.shields.io/maven-central/v/uy.kohesive.chillambda/chillambda.svg)](https://mvnrepository.com/artifact/uy.kohesive.chillambda) [![CircleCI branch](https://img.shields.io/circleci/project/kohesive/chillambda/master.svg)](https://circleci.com/gh/kohesive/chillambda/tree/master) [![Issues](https://img.shields.io/github/issues/kohesive/chillambda.svg)](https://github.com/kohesive/chillambda/issues?q=is%3Aopen) [![DUB](https://img.shields.io/dub/l/vibe-d.svg)](https://github.com/kohesive/chillambda/blob/master/LICENSE) [![Kotlin Slack](https://img.shields.io/badge/chat-kotlin%20slack%20%23kohesive-orange.svg)](http://kotlinslackin.herokuapp.com)


# Chillambda

Chillambda is used to serialize Kotlin lambdas in a safe and secure way so that
they can be executed elsewhere safely.  

When combined with [Cuarentena](https://github.com/kohesive/cuarentena), they can be security checked 
before/after serialization to ensure they are not attempting to access anything outside of a 
whitelist of classes or methods.  

Chillambda use cases:

* serialize a lambda to use as a binary script
* serialize a lambda to execute on another server 

### Gradle /Maven

Add add the following dependency:

```
uy.kohesive.chillambda:chillambda:1.0.0-BETA-08
```
