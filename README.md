# gradle_note
gradle note

# How to refer a local jar in gradle java project


step 1: put this in build.gradle
```java
apply plugin: 'java'
dependencies {
  compile files('libs/myhello-1.0.1.jar') 
}
``` 
step 2: run the following command
`gradle cleanEclipse eclipse`

step 3: referesh you java project
You should be able to see the jar is in th ereferenced libraries now.


