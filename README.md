# JDK-awesome-switch
A convenient  solution for switching between various JDK versions

```
export JAVA_7_HOME=$(/usr/libexec/java_home -v1.7)
export JAVA_8_HOME=$(/usr/libexec/java_home -v1.8)
export JAVA_9_HOME=$(/usr/libexec/java_home -v9)

alias java7='export JAVA_HOME=$JAVA_7_HOME'
alias java8='export JAVA_HOME=$JAVA_8_HOME'
alias java9='export JAVA_HOME=$JAVA_9_HOME'

#default java8
export JAVA_HOME=$JAVA_8_HOME
```
Then, type ```java8``` to use java8 SDK and etc...
