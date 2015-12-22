# CS180-Checkstyle
Checkstyle modified for use with CS18000 coding standards.

### Building
To build the executable jar for executing Checkstyle, navigate to the upper most directory of the project and run the following command.

`> jar cvfm META-INF/MANIFEST.MF [checkstylejarname.jar] *`

replacing **checkstylejarname.jar** with the name of the jar including the .jar extension.

### Usage
Checkstyle can be run from the command line.

`> java -jar [checkstylejarname.jar] -c [/checkstyleconfiguration.xml] [targetfiles]`

**checkstylejarname.jar** - the name you chose for the jar when packing it

**/checkstyleconfiguration.xml** - the Checkstyle XML configuration file (i.e. /google_checks.xml, /checkstyle.xml)

**targetfiles** - the files to run Checkstyle against. (i.e. SomeClass.java or *.java to run against all Java files)
