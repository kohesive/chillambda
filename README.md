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
uy.kohesive.chillambda:chillambda:1.0.0-BETA-01
```
