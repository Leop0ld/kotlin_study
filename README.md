Kotlin Study
===

Java < Kotlin

Install
---

You can install kotlin through brew in mac OS.

```shell
$ brew update
$ brew install kotlin
```

And you should install JDK([HERE](http://www.oracle.com/technetwork/java/javase/downloads/index.html))

Run
---

1. Compile

You can complie kotlin to java.

```shell
$ kotlinc hello.kt -d hello.jar
$ java -jar hello.jar
```

2. Run REPL

Use command below.

```
$ kotlinc-jvm
```

3. Run scripts

Run scripts using command line.
`.kts` NOT .kt !

```shell
$ kotlinc -script FILENAME.kts
```