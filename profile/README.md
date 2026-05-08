# What is WPILib?

WPILib is the standard software library and toolsuite provided for teams to write, test, and debug code for their *FIRST*&reg; Robotics Competition and *FIRST*&reg; Tech Challenge robots.  A [software library](https://en.wikipedia.org/wiki/Library_(computing)) is a collection of code that can be imported into and used by other software.  WPILib contains a set of useful classes and subroutines for interfacing with various parts of the *FIRST*&reg; control system (such as sensors, motor controllers, and the driver station), as well as an assortment of other utility functions.

## Supported languages

There are three officially-supported text-based languages for WPILib: Java, C++, and Python.  A considerable effort is made to maintain feature-parity between these languages, but WPILib may make features available to specific languages in cases where the feature represents a significant benefit to teams but cannot be implemented across all languages.  When possible, class and method names are kept identical or highly-similar.  Java, C++, and Python were chosen for the officially-supported languages due to their appropriate level-of-abstraction and broad use in both industry and education.

In general, C++ offers better high-end performance, at the cost of increased user effort (memory must be handled manually, and the C++ compiler does not do much to ensure user code will not crash at runtime).  Java and Python offer lesser performance, but much greater convenience.  Python users should take care to test their program to ensure that typos and other issues don't cause robot crashes, as Python is interpreted. New/inexperienced users are encouraged to use Java or Python.

## Source code and documentation

The primary documentation for WPILib is the [FIRST Robotics Competition Control System Documentation](https://docs.wpilib.org/).

Detailed API documentation can be found on the official documentation pages for each language:

 - [Java documentation](https://javadocs.wpilib.org)

 - [C++ documentation](https://cppdocs.wpilib.org)

 - [Python documentation](https://robotpy.readthedocs.io/projects/robotpy/en/latest/)

WPILib is an open-source library - the majority of the library source code is in the [allwpilib](https://github.com/wpilibsuite/allwpilib) mono-repo.   Python source code is in the [mostrobotpy](https://github.com/robotpy/mostrobotpy) mono-repo.  Various other tooling and infrastructure code is in other repositories under the [wpilibsuite](https://github.com/wpilibsuite) organization on GitHub.

## Installation

WPILib has a unified installer.  See the [WPILib Installation Guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html) for step-by-step installation instructions.

