# CalculatorWeek1Day5

keep Running into trouble with Github, it keeps asking for a security token.

1.  What are Listeners?
2. How does Java garbage collection work?
3. What is the android manifest used for?
4. Define the difference in Runtime and Compile Time.
5. What is reflection in JAVA?
6.  How does gradle work behind the scene.

Listener is short for Event Listener which is the interface responsible for handling events in java.
Each event that can be listened for such as onClick, or on press is what the listener is listening for.

Java Garbage collection is run by a mark and sweep algorithm, it finds objects that are unreachable in code. Which any object that is not being currently used is designated as garbage in its case. After locating these objects java reclaims the memory allocated to them.

The Android manifest is a xml file required by every android application, because it handles the package name for the application, it describes the activities-componenents-services of an application, determine which process will host application components, and it lists the classes that provides profiling and other information as the application is running. 

The before and after of software development compile time is the time taken to compile, source code written by the developer into machine code which is then transformed into an executable to be ran. While the executable is running is called Runtime. Compile time and runtime are also used to describe specific errors that occur during these times.

Reflection is a Java API that is meant to look at or change Methods classes, or interfaces at runtime. To use reflection in your project you must import java.lang.reflect.*;

Gradle is a dependency Manager that does a couple of things like allowing managing the classpath of your projects. 
It can add JAR files, directories or other projects to the build path of your application. 
It also supports the automatic download of your Java library dependencies, with a comand gradley with the background assistance of
groovy. You don't have to worry about finding and installing libraries or making sure everything is updated properly.







