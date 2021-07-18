# CSEnv
Environment Files on Ubuntu

## 1. Switch JDK Environment <change_jdk>

### Set up
First add the following shell script to the path environment file such as ~/bash.rc.
```shell
alias jdk6="source /<PATH>/<TO>/<CSEnv>/change_jdk jdk6"
alias jdk7="source /<PATH>/<TO>/<CSEnv>/change_jdk jdk7"
alias jdk8="source /<PATH>/<TO>/<CSEnv>change_jdk jdk8"

source /<PATH>/<TO>/<CSEnv>/change_jdk jdk8 s
```
Then modify jdk path (e.g.,jdk6,jdk7) in your change_jdk file.
### Example
```shell
jdk6 # switch jdk version to jdk_1.6
```
