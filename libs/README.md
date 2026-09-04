# NametagEdit Dependency

This directory contains optional dependencies that are not available in public Maven repositories.

## Adding NametagEdit

To use NametagEdit in this project:

1. Download `NametagEdit-4.5.23.jar` from [BuiltByBit](https://builtbybit.com/resources/nametagedit.98860/)
2. Place the JAR file in this directory as `NametagEdit-4.5.23.jar`
3. Uncomment the NameTagEdit dependency block in `pom.xml`
4. Run `mvn clean package`

**Note:** NametagEdit is not officially distributed through Maven Central or other public repositories, so it must be added manually.
