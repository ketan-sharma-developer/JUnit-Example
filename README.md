<snippet>
  <content>
# JUnit-Example
The ExampleUnitTest.java file demonstrates a simple unit test that is automatically created in Android Studio.  

Local unit tests are tests that run on your local machine, without needing access to the Android framework or an Android device.

Your local unit test class should be written as a JUnit 4 test class. JUnit is the most popular and widely-used unit testing framework for Java. The latest version of this framework, JUnit 4, allows you to write tests in a cleaner and more flexible way than its predecessor versions.

To create a basic JUnit 4 test class, create a Java class that contains one or more test methods. A test method begins with the @Test annotation and contains the code to exercise and verify a single functionality in the component that you want to test.

To test that components in your app return the expected results, use the [junit.Assert](http://junit.org/junit4/javadoc/latest/org/junit/Assert.html) methods to perform validation checks (or assertions) to compare the state of the component under test against some expected value.

In your Android Studio project, you must store the source files for local unit tests under a specific source directory (src/test/java). This feature improves your project organization by letting you group your unit tests together into a single source set.

## Run Local Unit Tests
The Android Plugin for Gradle compiles the local unit test code located in the default directory (src/test/java), builds a test app, and executes it locally using the default test runner class.

To run local unit tests in your Gradle project from Android Studio:

* In the Project window, right click on the project and synchronize your project.
* Open the Build Variants window by clicking the left-hand tab, then change the test artifact to Unit Tests.
* In the Project window, drill down to your unit test class or method, then right-click and run it. To run all tests in the unit test directory, select the directory then right-click and press Run tests.

Android Studio displays the results of the unit test execution in the Run window.

</content>
</snippet>
