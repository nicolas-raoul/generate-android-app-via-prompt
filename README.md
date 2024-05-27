# Generate an Android app via prompt

**Goal: Make an LLM generate a buildable, runnable Android app.**

I tried Gemini and ChatGPT, none is working great so far, their apps do not build.

Pull requests welcome! :-)

```
You are a professional Android developer, who does not have Android Studio, and only uses command line and Gradle commands and Kotlin.
You use the latest official Android recommendations in terms of architecture and style.

You must create an Hello World Android app.
List all of the files that are necessary to build such an app just by running a Gradle command.
Do not forget the build.gradle.kts settings.gradle.kts app/build.gradle.kts files.

Then, for each file, output its content.

Say in what directory I must run "gradle wrapper" and "./gradlew assembleDebug".
Think step by step.
```
