## Unit Testing course resources

### prerequisite
* JDK 1.8+ [download site](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* Intellij IDEA [download site](https://www.jetbrains.com/idea/download/)
* Git (optional) [download site](https://git-scm.com/downloads)

### initial develop environment steps

1. Install JDK 1.8
1. Set JAVA_HOME (make sure JAVA_HOME point to JDK 1.8 directory, especially there is other JDK version installed)
1. Install Intellij IDEA
1. download demo code
    * use command `git clone https://github.com/trend-university/unit-testing.git`
    * or download [zip](https://codeload.github.com/trend-university/unit-testing/zip/master) if without git installed
1. Import gradle project into IntelliJ IDEA ([How To](https://www.jetbrains.com/help/idea/2018.2/gradle.html#gradle_import)), use below settings
    * [x] Use auto-import
    * [x] Create directories for empty content roots automatically
    * group modules:
        * [x] using explicit module groups
        * [ ] using qualified names
    * [ ] Create separate module per source set
    * [x] Store generated project files externally
    * gradle:
        * [ ] Use default gradle wrapper
        * [x] Use gradle wrapper task configuration
        * [ ] Use local gradle distribution
1. Run first build from command line or IDE


### command line executing samples

* build all projects
  * Windows: `build.bat`
  * Linux: `build.sh`
* gradle task samples (assume use Windows OS)
  * run test-basic-junit4 test: `gradlew.bat clean test-basic-junit4:test`
  * run test-basic-testng fastTest: `gradlew.bat clean test-basic-testng:fastTest`
  * run test-basic-testng pitest: `gradlew.bat clean test-basic-testng:pitest`

---

### references
* [wiki Unit testing](https://en.wikipedia.org/wiki/Unit_testing)
* [List of Unit Test Frameworks](https://en.wikipedia.org/wiki/List_of_unit_testing_frameworks)
* [Python Testing Tools Taxonomy](https://wiki.python.org/moin/PythonTestingToolsTaxonomy)
* [xunit patterns](http://xunitpatterns.com/)
* [art of unit testing](http://artofunittesting.com/)

