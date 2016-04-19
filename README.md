# Java Development Kit (JDK) Annotations

This project contains [external annotations](https://wiki.eclipse.org/JDT_Core/Null_Analysis/External_Annotations) for
[Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/index.html) version 1.8.0.

These annotations allow Eclipse to perform null analysis.

## Usage

To build the annotations JAR, run

```bash
gradle build
```

This will create the file `jdk-annotations-1.8.0-r.1.jar`. Attach this file to the
Java Development Kit (JDK) library entry in your build path to have Eclipse use the annotations.