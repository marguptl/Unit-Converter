
# Unit Converter

**Unit Converter** is an Android application designed to provide quick and accurate unit conversions. Whether you're a student, engineer, scientist, or just need to convert units in your daily life, this app has you covered.

## Features

- **Multiple Conversion Categories**: Convert units across various categories such as length, weight, temperature, and more.
- **Simple User Interface**: Easily select the type of conversion, input your value, and get results instantly.
- **Customizable**: Add your own unit conversions or adjust existing ones.
  
## Setup

### Dependencies

- Android Gradle plugin: `7.0.2`
- Repositories:
  - Google's Maven repository
  - Maven Central
  - jCenter (Note: jCenter is going to shut down soon. Consider migrating to another repository.)

### Modules

- `:app` - Main application module

## How it Works

1. **Select Conversion Category**: Upon launching the app, select the category of conversion you're interested in (e.g., length, weight, temperature).
2. **Input Values**: Enter the value you wish to convert.
3. **Choose Units**: Select the unit you're converting from and the unit you're converting to.
4. **Get Results**: The converted value will be displayed instantly.

## Building the Application

To build the project, use the following command:

```
./gradlew build
```

## Cleaning the Build

To clean the project, use the following command:

```
./gradlew clean
```

## Report

A detailed report on the "Unit Converter" can be found [here](Unit%20Converter%20Report.html).

## Feedback and Contributions

We welcome feedback and contributions! Please open an issue or submit a pull request if you have suggestions or improvements.
