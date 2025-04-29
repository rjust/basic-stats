# Basic Statistics

Basic Statistics is a Java-based GUI program that computes statistics on a
set of numbers.
This implementation is intended to be used in a [`git bisect` exercise](ASSIGNMENT.md).


#### How to build Basic Statistics and run its tests from the terminal:

Run these commands from the Basic Statistics root directory, which contains the *build.gradle* build file.

1. Run `./gradlew compileJava` to compile Basic Statistics.

2. Run `./gradlew build` to compile and run tests.

3. Run `./gradlew clean` whenever you want to clean up the project (i.e., delete all generated files).

Note: **Always run `./gradlew clean build`** for the [`git bisect` exercise](ASSIGNMENT.md).
This will ensure that tests are re-run, if they have already been run after the
most recent code change.


#### How to run Basic Statistics from the terminal:

Run this command from the Basic Statistics root directory, which contains the
*build.gradle* build file.

Note: running the application is not required for the [`git bisect` exercise](ASSIGNMENT.md).

1. `./gradlew run`

The application's GUI will show up.

For Windows, use `gradlew.bat` instead of `./gradlew`.


#### Program features:
* Displays (at the bottom of the screen) a set of entered numbers.
* Computes the mean of the set of numbers.
* Computes the median of the set of numbers.
* Computes the mode of the set of numbers.
