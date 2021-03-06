[![Build Status](https://snap-ci.com/geb/geb-example-cucumber-jvm/branch/master/build_image)](https://snap-ci.com/geb/geb-example-cucumber-jvm/branch/master)

# Description

This is an example project for using [Geb](http://geb.codehaus.org/ "Geb - Groovy Browser Automation")
with the [Cucumber-JVM](http://cukes.info/install-cucumber-jvm.html "Cucumber JVM") testing framework.

# Usage

This example is a [Gradle](http://www.gradle.org/ "Gradle") project and uses the
[Gradle Cucumber Plugin](https://github.com/samueltbrown/gradle-cucumber-plugin/ "Gradle Cucumber Plugin").
The project is using the [Gradle wrapper](http://www.gradle.org/docs/current/userguide/gradle_wrapper.html),
so if you don't need to have Gradle installed if you execute the appropriate script in the project directory
and Gradle will be downloaded for you.

To run the tests, just run `./gradlew cucumber` on *nix or `gradlew.bat cucumber` on Windows.

See the `src/test/resources/GebConfig.groovy` file for how to run the tests with different browsers.

# Questions and issues

Please ask questions on [Geb user mailing list](http://xircles.codehaus.org/lists/user@geb.codehaus.org) and raise issues in [Geb issue tracker](https://jira.codehaus.org/browse/GEB).
