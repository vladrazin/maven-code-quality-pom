## maven-code-quality-pom

-----

  - Last Published: 2017-11-10|
  - Version: 0.0.1-SNAPSHOT

<!-- end list -->

  - Code Quality Reports
  - [Unit Tests](surefire-report.md "Unit Tests")
      - [Code Coverage
        (JaCoCo)](jacoco/index.md "Code Coverage (JaCoCo)")
      - [Results (Surefire)](surefire-report.md "Results (Surefire)")
      - [Unit Test
        Javadocs](testapidocs/index.md "Unit Test Javadocs")
      - [Unit Test Source
        Code](xref-test/index.md "Unit Test Source Code")
  - [Coding Standards](checkstyle.md "Coding Standards")
      - [Checkstyle](checkstyle.md "Checkstyle")
      - [CPD](cpd.md "CPD")
      - [FindBugs](findbugs.md "FindBugs")
      - [JDepend](jdepend-report.md "JDepend")
      - [PMD](pmd.md "PMD")
  - [Dependencies](dependency-updates-report.md "Dependencies")
  - [Security Vulnerabilities](codenarc.md "Security Vulnerabilities")
  - [Source Code](xref/index.md "Source Code")
      - [Java](xref/index.md "Java")
      - [Javadocs](apidocs/index.md "Javadocs")
  - Contributions
  - [Change Log](changelog.md "Change Log")
  - [Contributors](dev-activity.md "Contributors")
  - [Commits/Changes](file-activity.md "Commits/Changes")
  - Project Documentation
  - [Project Information](project-info.md "Project Information")
  - [Project Reports](#)
      - [Surefire Report](surefire-report.md "Surefire Report")
      - [JaCoCo](jacoco/index.md "JaCoCo")
      - [JaCoCo
        Aggregate](jacoco-aggregate/index.md "JaCoCo Aggregate")
      - [CodeNarc
        Report](codenarc.md "CodeNarc Report")
      - [FindBugs](findbugs.md "FindBugs")
      - [Checkstyle](checkstyle.md "Checkstyle")
      - [CPD](cpd.md "CPD")
      - [PMD](pmd.md "PMD")
      - [JDepend](jdepend-report.md "JDepend")
      - [dependency-check](dependency-check-report.md "dependency-check")
      - [Dependency
        Analysis](dependency-analysis.md "Dependency Analysis")
      - [Dependency Updates
        Report](dependency-updates-report.md "Dependency Updates Report")
      - [Plugin Updates
        Report](plugin-updates-report.md "Plugin Updates Report")
      - [Property Updates
        Report](property-updates-report.md "Property Updates Report")
      - [Source Xref](xref/index.md "Source Xref")
      - [Test Source Xref](xref-test/index.md "Test Source Xref")
      - [Javadoc](apidocs/index.md "Javadoc")
      - [Test Javadoc](testapidocs/index.md "Test Javadoc")
      - [Change Log](changelog.md "Change Log")
      - [File Activity](file-activity.md "File Activity")
      - [Developer Activity](dev-activity.md "Developer Activity")
      - [Third Parties](third-party-report.md "Third Parties")

-----

[![Built by
Maven](./images/logos/maven-feather.png)](http://maven.apache.org/ "Built by Maven")

## Generated Reports

This document provides an overview of the various reports that are
automatically generated by [Maven](http://maven.apache.org) . Each
report is briefly described
below.

### Overview

| Document                                                    | Description                                                                                                                                                                                                                                                                               |
| ----------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Surefire Report](surefire-report.md)                     | Report on the test results of the project.                                                                                                                                                                                                                                                |
| [JaCoCo](jacoco/index.md)                                 | JaCoCo Coverage Report.                                                                                                                                                                                                                                                                   |
| [JaCoCo Aggregate](jacoco-aggregate/index.md)             | JaCoCo Aggregate Coverage Report.                                                                                                                                                                                                                                                         |
| [CodeNarc Report](codenarc.md)                            | Generates a source code report with the CodeNarc Library.                                                                                                                                                                                                                                 |
| [FindBugs](findbugs.md)                                   | Generates a source code report with the FindBugs Library.                                                                                                                                                                                                                                 |
| [Checkstyle](checkstyle.md)                               | Report on coding style conventions.                                                                                                                                                                                                                                                       |
| [CPD](cpd.md)                                             | Duplicate code detection.                                                                                                                                                                                                                                                                 |
| [PMD](pmd.md)                                             | Verification of coding rules.                                                                                                                                                                                                                                                             |
| [JDepend](jdepend-report.md)                              | JDepend traverses Java class file directories and generates design quality metrics for each Java package. JDepend allows you to automatically measure the quality of a design in terms of its extensibility, reusability, and maintainability to manage package dependencies effectively. |
| [dependency-check](dependency-check-report.md)            | Generates a report providing details on any published vulnerabilities within project dependencies. This report is a best effort and may contain false positives and false negatives.                                                                                                      |
| [Dependency Analysis](dependency-analysis.md)             | Dependency analysis of the project (used declared, used undeclared, unused declared)                                                                                                                                                                                                      |
| [Dependency Updates Report](dependency-updates-report.md) | Provides details of the dependencies which have updated versions available.                                                                                                                                                                                                               |
| [Plugin Updates Report](plugin-updates-report.md)         | Provides details of the plugins used by this project which have newer versions available.                                                                                                                                                                                                 |
| [Property Updates Report](property-updates-report.md)     | Provides details of properties which control versions of dependencies and/or plugins, and indicates any newer versions which are available.                                                                                                                                               |
| [Source Xref](xref/index.md)                              | HTML based, cross-reference version of Java source code.                                                                                                                                                                                                                                  |
| [Test Source Xref](xref-test/index.md)                    | HTML based, cross-reference version of Java test source code.                                                                                                                                                                                                                             |
| [Javadoc](apidocs/index.md)                               | Javadoc API documentation.                                                                                                                                                                                                                                                                |
| [Test Javadoc](testapidocs/index.md)                      | Test Javadoc API documentation.                                                                                                                                                                                                                                                           |
| [Change Log](changelog.md)                                | Generated change log report from SCM.                                                                                                                                                                                                                                                     |
| [File Activity](file-activity.md)                         | Generated file activity report from SCM.                                                                                                                                                                                                                                                  |
| [Developer Activity](dev-activity.md)                     | Generated developer activity report from SCM.                                                                                                                                                                                                                                             |
| [Third Parties](third-party-report.md)                    | Provides details of third parties of the project.                                                                                                                                                                                                                                         |

-----

Copyright ©2017 [gregswindle](https://github.com/gregswindle). All
rights reserved.