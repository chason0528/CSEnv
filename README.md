# CSEnv
Environment Files on Ubuntu

## Switch JDK Environment

### Set up
Add the shell config script to the path environment file such as ~/bash.rc》
```shell
alias jdk6="source /<PATH>/<TO>/<CSEnv>/change_jdk jdk6"
alias jdk7="source /<PATH>/<TO>/<CSEnv>/change_jdk jdk7"
alias jdk8="source /<PATH>/<TO>/<CSEnv>change_jdk jdk8"

source /<PATH>/<TO>/<CSEnv>/change_jdk jdk8 s
```

### Example
```shell
jdk6 # switch jdk version to jdk_1.6
```
