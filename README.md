# Simple Java Application

## Documentation

This repository contains a simple Java application that demonstrates the basic structure and functionality of a typical Java project.

## Project Structure

```
Simple-Java/
├── src/                  # Source files
│   └── main/            # Main application source
├── lib/                 # Libraries
├── test/                # Test cases
├── build.gradle         # Build configuration file
└── README.md            # Project documentation
```

## Prerequisites

Before you begin, ensure you have met the following requirements:

- JDK 11 or above installed on your machine.
- Gradle installed for building the project.

## Build Instructions

To build the project, follow these steps:

1. Navigate to the project directory:
    ```bash
    cd Simple-Java
    ```

2. Run the build command:
    ```bash
    gradle build
    ```

## Jenkins Deployment Steps

To deploy this application using Jenkins, follow these steps:

1. Set up a Jenkins job for this repository.
2. Configure the job to pull the code from the `Surajbasheer/Simple-Java` repository.
3. In the build steps, add the command to build the application:
    ```bash
    gradle build
    ```
4. (Optional) Configure post-build actions to deploy the application to your desired environment.
