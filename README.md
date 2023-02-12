# CI & CD
## This is note for CI/CD implementation.

Tested on MacOS Monterey 12.6.3

---

### Step 1: Check Java version. 
I am using 1.8.0_241. 

```shell
% java -version
java version "1.8.0_241"
% javac -version
javac 1.8.0_241
```

If you requie to install go to https://www.oracle.com/java/technologies/downloads/archive/ and download required version.

---

### Step 2: Check Java Home.

```shell
echo $JAVA_HOME
/Library/Java/JavaVirtualMachines/jdk1.8.0_241.jdk/Contents/Home
```

If you don't see any output, edit your terminal's profile for zsh.
```shell
vim ~/.zshrc
```
If you're not using zsh, this will be:
```shell
vim ~/.bash_profile
```

Add your java home location.
```shell
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_241.jdk/Contents/Home
```
