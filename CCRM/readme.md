Campus Course Records Manager (CCRM)
Project Overview
Campus Course Records Manager (CCRM) is a console-based Java application that manages student records, courses, enrollments, grading, transcript generation, and file operations like import/export and backup.
It demonstrates core Java SE features including OOP principles, file handling with NIO.2, Java Streams, DateTime API, custom exceptions, and design patterns.

How to Run
JDK Version: Java 11 or higher recommended

Compile:

text
javac -d bin $(find src -name "*.java")
Run:

text
java -cp bin edu.ccrm.Main
Use the console menu to navigate through options.

Evolution of Java (Short Bullets)
1995: Java 1.0 launched - “Write once, run anywhere” philosophy

1998: Java 2 introduced Swing UI, Collections Framework

2004: Java 5 released with generics, annotations, enhanced for-loop

2014: Java 8 with Lambda expressions, Stream API, DateTime API

2017: Java 9 with modules system (JPMS)

2021: Java 17 LTS with improved pattern matching, sealed classes

Java ME vs SE vs EE
Java ME (Micro Edition) is a specialized edition of Java designed for mobile devices and embedded systems with limited resources. It provides a lightweight runtime environment and a subset of Java APIs tailored for constrained devices like feature phones, IoT gadgets, and small embedded devices. Java ME applications are typically small and optimized for low memory and processing power.

Java SE (Standard Edition) is the core Java platform used for creating general-purpose, desktop, and server applications. It includes a comprehensive set of libraries and APIs for programming user interfaces, networking, file I/O, concurrency, and more. Java SE forms the foundation for other editions and provides the Java Virtual Machine (JVM) to ensure platform independence.

Java EE (Enterprise Edition) builds on top of Java SE and offers a robust set of APIs and services for developing large-scale, multi-tiered, scalable, and secure enterprise applications. It includes components for web services, servlets, Enterprise JavaBeans (EJBs), messaging, and persistence, and typically runs in an application server environment suitable for complex business applications.

Windows Installation & Eclipse Setup
Windows JDK Installation
Download JDK installer from Oracle or OpenJDK.

Run installer and follow prompts.

Set JAVA_HOME environment variable:

Open Environment Variables → New system variable JAVA_HOME set to JDK path

Edit Path variable, add %JAVA_HOME%\bin

Verify install by cmd:


java -version  
javac -version
Eclipse Setup
Download Eclipse IDE for Java Developers.

Open Eclipse and create a new Java Project.

Add your source code folder (src) to the project.

Ensure JDK is configured as the runtime in Eclipse preferences.

To run, right-click Main.java → Run As → Java Application.



To enable assertions when running:

text
java -ea -cp bin edu.ccrm.Main
To enable for all classes including libraries:

text
java -ea:edu.ccrm... -cp bin edu.ccrm.Main
To disable assertions:

text
java -da -cp bin edu.ccrm.Main

The Screenshot Shows the working of the project 

<img width="862" height="265" alt="Screenshot 2025-09-23 at 8 30 19 PM" src="https://github.com/user-attachments/assets/54e0b7bc-7809-47a2-8a6a-ff18f7fe6eb0" />
<img width="867" height="725" alt="Screenshot 2025-09-23 at 8 29 50 PM" src="https://github.com/user-attachments/assets/09b1f065-b0b7-4459-aa4f-0e1ee841820c" />
<img width="858" height="628" alt="Screenshot 2025-09-23 at 8 29 31 PM" src="https://github.com/user-attachments/assets/12f9cbc5-5109-4605-9e4a-f732249faf6d" />
<img width="797" height="300" alt="Screenshot 2025-09-23 at 8 21 02 PM" src="https://github.com/user-attachments/assets/96df23e2-d1c2-4033-a115-8bb565c0e577" />




