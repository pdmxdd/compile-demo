# Java Compiliation Demo

## Compile then Run

To compile the Main class we need to use the javac tool on our Main.java file:

```
javac Main.java
```

This will create a new file called Main.class:

```
ls
```

Do you see the new file?

We can now run this file with the JVM:

```
java Main
```

The simple program just prints to the terminal and you should see the output.

## Compile & Run in One

You can also ask Java to compile and run all in one step with:

```
java Main.java
```

This tells java to compile the file first and then pass that result directly to the JVM to be run. You will notice this takes just a little longer to run than the compiled first program. This is a pattern you will see with ALL compiled languages.
