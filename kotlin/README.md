# Pairing Induction Exercise

## Quick Start

Tests can be executed in the terminal, from the root folder of the project:

```bash
./gradlew test
```

You can also run the tests automatically every time there are changes in the filesystem:

```bash
./gradlew -t test
```

Or you can use your IDE to run the tests


## Requirements

- Java JDK 8+

With SDKMAN (Recommended - see below how to install SDKMAN):

```bash
sdk install java
```

Or with Homebrew:

```bash
brew tap caskroom/versions
brew cask install java8
```

- Kotlin 1.3.20+

_NOTE_: If you are using IntelliJ IDEA as IDE, it already comes with `kotlin` bundled in it, and it is not necessary to install it, but if you are using another editor, then you can install it with:

With SDKMAN (Recommended):

```bash
sdk install kotlin
```

Or with Homebrew:

```bash
brew install kotlin
```


### Optional

- SDKMAN

This is a tool that helps managing the installation and management of different versions of the binaries for different languages, build tools, etc. around the JVM.

The installation instructions can be found at https://sdkman.io/install

With this tool, you can install `java`, `kotlin` and `gradle`, also with multiple versions at the same time, and activate different versions easily. For example:

Java Examples:

```bash
sdk list java
sdk install java
sdk install java 8.0.201-zulu
sdk install java 11.0.2-zulu
sdk use java 8.0.201-zulu
sdk use java 11.0.2-zulu
```

Kotlin Examples:

```bash
sdk list kotlin
sdk install kotlin
sdk install kotlin 1.3.20
sdk install kotlin 1.2.10
sdk use kotlin 1.2.10
sdk use kotlin 1.3.20
```

For a full list of all the tools that can be managed with SDKMAN:

```bash
sdk list
```

- Gradle

We are using `gradle` as our building and dependency management tool,
but since we are using the wrapper, we don't need to have it installed.

But in case you want to have it installed locally anyways, you can do it with either:

With SDKMAN (Recommended)

```bash
sdk install gradle
```

or with Homebrew:

```bash
brew install gradle
```
