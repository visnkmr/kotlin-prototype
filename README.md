# Kotlin Hello World

A simple Kotlin project that prints "Hello World" to the terminal.

## Prerequisites

- Java 17 or higher
- Gradle (or use the included wrapper)

## Running the Project

### Option 1: Using Gradle (Recommended)

1. Open a terminal in the project directory.
2. Run the following command:
   ```
   gradle run
   ```
   This will compile and run the application, printing "Hello World" to the console.

### Option 2: Using the JAR file

1. Build the project:
   ```
   gradle build
   ```
2. Run the JAR:
   ```
   java -jar build/libs/drawcanvas-1.0-SNAPSHOT.jar
   ```
   This will print "Hello World" instantly.

## Project Structure

- `src/main/kotlin/Main.kt`: Main Kotlin file with the entry point.
- `build.gradle.kts`: Gradle build configuration.
- `.gitignore`: Git ignore file for excluding build artifacts and IDE files.

## Notes

- The first run may take longer due to downloading dependencies.
- Subsequent runs will be faster as dependencies are cached.
