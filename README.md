# campus-course-records-manager
The Campus Course &amp; Records Manager (CCRM) is a console-based Java SE app to manage students, courses, enrollments, and transcripts. It supports file import/export, GPA computation, and backups. Built with OOP, design patterns, NIO.2, Streams, and robust exception handling, it demonstrates core to advanced Java concepts.

Evolution of Java (Timeline)

1995 – Java 1.0 released by Sun Microsystems.
1998 – Java 2 introduces J2SE, J2EE, J2ME.
2004 – Java 5: generics, annotations, enums.
2011 – Java 7: NIO.2, try-with-resources.
2014 – Java 8: lambdas, Streams, Date/Time API
2017 – Java 9: modules (Project Jigsaw).
2019+ – Six-month release cycle (Java 11 LTS, 17 LTS, etc.).

| Feature        | Java ME (Micro)             | Java SE (Standard)                    | Java EE (Enterprise)               |
| -------------- | --------------------------- | ------------------------------------- | ---------------------------------- |
| Target Devices | Embedded, mobile, IoT       | Desktop apps, CLI tools               | Web, enterprise-scale apps         |
| Libraries      | Minimal, lightweight        | Core Java libraries (Collections, IO) | Adds Servlets, JSP, EJB, JPA, etc. |
| Typical Use    | Smart cards, feature phones | General apps, standalone tools        | Banking, e-commerce, ERP systems   |

Java Architecture (JDK, JRE, JVM)

JDK (Java Development Kit) – Includes JRE + compiler (javac), debugger, and dev tools.
JRE (Java Runtime Environment) – Contains JVM + libraries required to run apps.
JVM (Java Virtual Machine) – Executes Java bytecode, provides portability across platforms.


download JDK (latest LTS, e.g., Java 17) from Oracle
.
Run installer and follow setup steps.
Set environment variables:
Add JAVA_HOME = C:\Program Files\Java\jdk-17
Update PATH: %JAVA_HOME%\bin
Verify installation:
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/7510717d-7582-4048-bac8-569337f51f6b" />





Using Eclipse IDE

Download & install Eclipse IDE for Java Developers.
Open Eclipse and select a workspace folder.
Create a new project:
File → New → Java Project → Enter name (e.g., CCRMProject).
Add packages (edu.ccrm.domain, edu.ccrm.service, etc.).
Create the Main.java class.
Run configurations:
Right-click Main → Run As → Java Application.

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/2b119188-487f-4010-baa8-253279ad0b41" />
