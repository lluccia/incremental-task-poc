# Gradle incremental task inputs POC
<https://docs.gradle.org/current/dsl/org.gradle.api.tasks.incremental.IncrementalTaskInputs.html>

Task execution affects only changed files.

## Build
```shell
./gradlew reverse
```
files in `src/reverse` will be reversed on build dir `build/reverse` (only changed files)
