# What is WPILib?

The WPI Robotics Library (WPILib) is the standard software library provided for teams to write code for their FIRST&reg; Robotics Competition (FRC&reg;) robots.  A [software library](https://en.wikipedia.org/wiki/Library_(computing)) is a collection of code that can be imported into and used by other software.  WPILib contains a set of useful classes and subroutines for interfacing with various parts of the FRC control system (such as sensors, motor controllers, and the driver station), as well as an assortment of other utility functions.

## Supported languages

There are two versions of WPILib, one for each of the two officially-supported text-based languages: WPILibJ for Java, and WPILibC for C++.  A considerable effort is made to maintain feature-parity between these two languages - library features are not added unless they can be reasonably supported for both Java and C++, and when possible the class and method names are kept identical or highly-similar.  While unofficial community-built support is available for some other languages, notably [python](https://robotpy.readthedocs.io/en/stable/), the main WPILib project only supports Java and C++.  Java and C++ were chosen for the officially-supported languages due to their appropriate level-of-abstraction and ubiquity in both industry and high-school computer science classes.

In general, C++ offers better high-end performance, at the cost of increased user effort (memory must be handled manually, and the C++ compiler does not do much to ensure user code will not crash at runtime).  Java offers lesser performance, but much greater convenience.  New/inexperienced users are strongly encouraged to use Java.

## Source code and documentation

The primary documentation for WPILib is the [FIRST Robotics Competition Control System Documentation](https://docs.wpilib.org/).

WPILib is an open-source library - the entirety of the library source code is in the [allwpilib](https://github.com/wpilibsuite/allwpilib) mono-repo.  The Java and C++ source code can be found in the WPILibJ and WPILibC source directories:

 - [Java source code](https://github.com/wpilibsuite/allwpilib/tree/main/wpilibj/src/main/java/edu/wpi/first/wpilibj)

 - [C++ source code](https://github.com/wpilibsuite/allwpilib/tree/main/wpilibc/src/main/native/cpp)

While users are strongly encouraged to read the source code to resolve detailed questions about library functionality, more-concise documentation can be found on the official documentation pages for WPILibJ and WPILibC:

 - [Java documentation](https://first.wpi.edu/wpilib/allwpilib/docs/release/java/)

 - [C++ documentation](https://first.wpi.edu/wpilib/allwpilib/docs/release/cpp/)

## Installation

WPILib has a unified installer.  See the [WPILib Installation Guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html) for step-by-step installation instructions.

