# JVM Readings


## JVM Internals

* http://blog.jamesdbloom.com/JVMInternals.html
* [JVM for Dummies](https://www.slideshare.net/CharlesNutter/jvm-for-dummies-oscon-2011), good bytecode overview

## GC

* [Garbage-First Garbage Collection](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.63.6386&rep=rep1&type=pdf)
* [Understanding Garbage Collection](http://www.slideshare.net/dougqh/understanding-garbage-collection)
* [Shenandoah](https://dl.acm.org/citation.cfm?id=2972210)


## JIT

* [JVM Mechanics: When Does the JVM JIT & Deoptimize?](http://www.slideshare.net/dougqh/jvm-mechanics-when-does-the)
* [JITWatch](https://github.com/AdoptOpenJDK/jitwatch)


## Profiling

* [JMH introduction](http://java-performance.info/jmh/)
  * Sample JMH [benchmark code](http://hg.openjdk.java.net/code-tools/jmh/file/tip/jmh-samples/src/main/java/org/openjdk/jmh/samples/), read through all of them


## Method Dispatch

This is a good blog post about the cost of polymorphic dispatches. But more importantly, it is a good blog post to understand performance measurement methodology.

http://shipilev.net/blog/2015/black-magic-method-dispatch/


## Safepoints

http://chriskirk.blogspot.com/2013/09/what-is-java-safepoint.html


## Intrinsics

http://www.slideshare.net/RednaxelaFX/green-teajug-hotspotintrinsics02232013


