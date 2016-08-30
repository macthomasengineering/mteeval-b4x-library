#B4X Expression Compiler and Eval Library

MteEval is a library for compiling and evaluating expressions at runtime. Expressions are converted to bytecode and then executed on demand with a simple virtual machine.

There are three builds of the library available: Android (B4A), iOS (B4i), and Java (B4J).  

##Usage

MteEval adopts the "code block" format from the venerable 1990's xBase compiler Clipper 5.X.

```clipper
{|<parameters,>|<expression>}
```

##Linking

* To use the Android or Java editions, add the .JAR and .XML files to your Additional Libraries folder and check the library through the Libraries Manager.  
* For iOS, add the modules CODEBLOCK.BAS, CODEGEN.BAS, PCODE.BAS, and RUN.BAS to your project.








