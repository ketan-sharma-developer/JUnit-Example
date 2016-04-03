<snippet>
  <content>
# JUnit-Example
This java file demonstrates a simple unit test that can be used in Android.  
Local unit tests are tests that run on your local machine, without needing access to the Android framework or an Android device.
our local unit test class should be written as a JUnit 4 test class. JUnit is the most popular and widely-used unit testing framework for Java. The latest version of this framework, JUnit 4, allows you to write tests in a cleaner and more flexible way than its predecessor versions. Unlike the previous approach to Android unit testing based on JUnit 3, with JUnit 4, you do not need to extend the junit.framework.TestCase class. You also do not need to prefix your test method name with the ‘test’ keyword, or use any classes in the junit.framework or junit.extensions package.

To create a basic JUnit 4 test class, create a Java class that contains one or more test methods. A test method begins with the @Test annotation and contains the code to exercise and verify a single functionality in the component that you want to test.
To test that components in your app return the expected results, use the [junit.Assert](http://http://junit.org/junit4/javadoc/latest/org/junit/Assert.html) methods to perform validation checks (or assertions) to compare the state of the component under test against some expected value.

In your Android Studio project, you must store the source files for local unit tests under a specific source directory (src/test/java). This feature improves your project organization by letting you group your unit tests together into a single source set.
</content>
</snippet>
