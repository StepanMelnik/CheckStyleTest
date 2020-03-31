# CheckStyleTest
A simple java project to test how checkstyle works in parent project.

## Tune eclipse
Eclipse should use **m2e** connector as specified in [Checkstyle in eclipse](https://checkstyle.org/eclipse.html).

When the project is imported in eclipse as maven project, checkstyle plugin should be activated in the project properties.

Also Properties -> Checkstyle -> Main configuration should use the following settings:
- java-sources-checkstyle-main checkstyle should validate ^src/main/java/.*\.java sources;
- java-sources-checkstyle-test checksyule should validate ^src/test/java/.*\.java sources.

### Classes
The project contains a few classes only to check if parent project validates violations properly in java code.

The result of violations created in checkstyle_result_*.xml output files.

