### How to start
Download dependencies using:
`mvn clean verify`

### Specify Browser
Specify Browser to execute tests, use below switches:
* `-Dbrowser=firefox`
* `-Dbrowser=chrome`
* `-Dbrowser=ie`
* `-Dbrowser=edge`
* `-Dbrowser=opera`

### Using headless mode
Specify to execute tests using headless mode or not, use below switches:
* `-Dheadless=true`
* `-Dheadless=false`

### Troubleshooting:
Not working? try below commands:
* `mvn clean verify -Doverwrite.binaries=true`
* Delete the `selenium_standalone_binaries` folder in your resources directory

### Build status:
[![Build Status](https://travis-ci.org/pwalaszkowski/java_maven_selenium_travis_ci_example.svg?branch=main)](https://travis-ci.org/pwalaszkowski/java_maven_selenium_travis_ci_example)