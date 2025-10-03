📋 Project Overview

* This project sets up a complete CI/CD pipeline where:
 * A basic Java application is automatically built using Maven
 * Jenkins orchestrates the build process
 * Everything runs on an AWS EC2 Ubuntu instance
 * Successful builds produce executable JAR files

🏗️ Project Summary

* We created a complete CI/CD pipeline where Jenkins automatically builds a Java application using Maven on an EC2 Ubuntu instance.
* What We Accomplished:

 * Set up the infrastructure - Configured an EC2 Ubuntu instance with Java, Maven, and Jenkins
 * Created the application - Built a simple "Hello World" Java app with proper Maven structure
 * Configured Jenkins - Set up a freestyle job that automatically:
 * Copies the source code from the filesystem
 * Runs Maven build commands (clean package)
 * Compiles the Java code and packages it into a JAR file
 * Executes the application to verify it works
 * Established automation - Every time we trigger the build, Jenkins automatically compiles, tests, and packages our application
 * Verified success - Confirmed the pipeline works by seeing "Hello, Jenkins + Maven!" output and BUILD SUCCESS status
 * The Outcome: We now have a working CI/CD pipeline that can automatically build our Java application with a single click, demonstrating the fundamental concept of continuous integration where code changes can be automatically tested and packaged.

https://github.com/CSD-FX/Task-8_Elevate_Labs/raw/master/images/Screenshot%202025-10-03%20at%2011.51.11%20AM.png

https://github.com/CSD-FX/Task-8_Elevate_Labs/raw/master/images/Screenshot%202025-10-03%20at%2011.51.48%20AM.png

https://github.com/CSD-FX/Task-8_Elevate_Labs/raw/master/images/Screenshot%202025-10-03%20at%2012.30.51%20PM.png
