# Java Learning - Platform Independence Test

To understand the difference between platform-dependent and platform-independent programming languages using C and Java.

---

## 💻 C Program

### Windows

```
gcc hello.c -o hello.exe
a.exe
```

### Linux

```
gcc hello.c -o hello
./a.out
```

### 🔍 Observation

* Different executable files are generated:

  * Windows → `hello.exe`
  * Linux → ./ `a.out`
* Program must be compiled separately for each OS

---

## ☕ Java Program

### Windows & Linux

```
javac Hello.java
java Hello
```

### 🔍 Observation

* Same `.class` file runs on both operating systems
* No need to recompile for different platforms

---

* C is **platform dependent** because it generates machine-specific executable files.
* Java is **platform independent** because it uses JVM to run the same bytecode on different systems.

---

Final Result

This experiment proves:

*C → Compile separately for each OS
*Java → Write Once, Run Anywhere
