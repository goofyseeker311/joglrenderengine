# JOGL Render Engine
JOGL Render Engine

# Installing and running

Primary running method from console command after downloading javarenderengine.jar file (one line command):

```
java --add-exports java.base/java.lang=ALL-UNNAMED --add-exports java.desktop/sun.java2d=ALL-UNNAMED
     --add-opens java.desktop/sun.awt=ALL-UNNAMED --add-opens java.desktop/sun.awt.windows=ALL-UNNAMED
     -jar javarenderengine.jar
```

Alternative way of running the program is to open a console window on the javarenderengine.jar location and type command
"java -jar javarenderengine.jar", which will also show debug output text on the console window. Otherwise console debug output
can be activated in the Java Control Panel or Configure Java application -> Advanced -> Java console -> Show console and
Miscellaneous -> Place Java icon in system tray if the java icon is not already visible on your operating system tray.

# Development and distribution

Install Eclipse IDE for Java Developers 2023‑12 (or later) and load the repository as a java project into the IDE:
https://www.eclipse.org/downloads/packages/release/2023-12/r/eclipse-ide-java-developers

Download JOGL version 2.5.0 or later for your platform at https://jogamp.org/.

To make an executable .jar file, export runnable .jar from eclipse with package required libraries into generated JAR.
After generating application .jar, add platform specific JOGL jars and binaries to the root of the .jar zip file.

# Licence (FSNLR -- Free Software No License Required)
This is free software which does not require any license agreement under government enforcement to limit it's freedom of usage for any purpose.

