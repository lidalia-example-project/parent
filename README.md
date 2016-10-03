# Example Multi-Module Gradle Build

To build:

```
git clone --recursive git@github.com:lidalia-example-project/parent.git
cd parent
./gradlew build
```

This is an example of a multi-module gradle build where the child modules are conceived as stand-alone projects, each with their own git
repo and (theoretical!) CI build and deployment, using a Maven style local SNAPSHOT dependency resolution.

Full details in my blog post:
[Gradle Multi-Project Build with local SNAPSHOT dependency resolution](http://blog.lidalia.org.uk/2016/10/gradle-multi-project-build-with-local.html).
