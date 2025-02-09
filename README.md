<p align="center">
    <img src="https://img.icons8.com/nolan/512/1A6DFF/C822FF/graduation-cap.png" width="200" style="border-radius: 20px;" />
</p>
            

<p align="center">
    <h1 align="center">SLR_Parsing</h1>
</p>


<p align="center">
  <img src="https://img.shields.io/github/license/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="license">
  <img src="https://img.shields.io/github/last-commit/Eemayas/SLR_Parsing?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
  <img src="https://img.shields.io/github/languages/top/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="repo-top-language">
  <img src="https://img.shields.io/github/languages/count/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="repo-language-count">
  <img src="https://img.shields.io/github/actions/workflow/status/Eemayas/SLR_Parsing/build.yml?branch=main&style=flat&color=0080ff" alt="build-status">
  <img src="https://img.shields.io/github/issues/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="open-issues">
  <img src="https://img.shields.io/github/forks/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="forks">
  <img src="https://img.shields.io/github/stars/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="stars">
  <img src="https://img.shields.io/github/issues-pr/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="pull-requests">
  <img src="https://img.shields.io/github/contributors/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="contributors">
  <img src="https://img.shields.io/github/commit-activity/m/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="commit-activity">
  <img src="https://img.shields.io/github/languages/code-size/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="code-size">
  <img src="https://img.shields.io/github/repo-size/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="repo-size">
  <img src="https://img.shields.io/github/downloads/Eemayas/SLR_Parsing/total?style=flat&color=0080ff" alt="downloads">
  <img src="https://img.shields.io/github/sponsors/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="sponsors">
  <img src="https://img.shields.io/github/v/release/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="release-version">
  <img src="https://img.shields.io/codecov/c/github/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="coverage">
  <img src="https://img.shields.io/codeclimate/quality/a/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="code-quality">
  <img src="https://img.shields.io/david/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="dependencies">
  <img src="https://img.shields.io/david/dev/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="dev-dependencies">
  <img src="https://img.shields.io/snyk/vulnerabilities/github/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="security">
  <img src="https://img.shields.io/website?style=flat&color=0080ff&url=https%3A%2F%2Fexample.com" alt="performance">
  <img src="https://img.shields.io/github/commit-activity/y/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="activity">
  <img src="https://img.shields.io/docsify/docs?style=flat&color=0080ff" alt="documentation">
  <img src="https://img.shields.io/github/v/tag/Eemayas/SLR_Parsing?style=flat&color=0080ff" alt="version">
</p>
    

<p align="center">
    <em>Constructed using the following tools and technologies:</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=Java&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F.svg?style=for-the-badge&logo=Spring-Boot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Maven-ED8B00?style=for-the-badge&logo=Maven&logoColor=white" alt="Maven">
</p>
    

      

# Project Overview

This project implements the backend of an SLR (Simple LR) parser, a type of parsing algorithm used to analyze context-free grammars. The backend is built using Spring Boot and handles the parsing logic, which includes efficient grammar analysis and table generation. The parser supports various input formats and grammar rules, providing a robust and efficient solution for syntax analysis.

# Table of Content

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setup Instructions](#setup-instructions)
  - [Running the Project](#running-the-project)
  - [Tests](#tests)
  - [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
    - [Contributing Guidelines](#contributing-guidelines)
- [Contributors](#contributors)
- [License](#license)

# Key Features
- **LR(1) Parsing Algorithm**: The code implements the LR(1) parsing algorithm, which is a popular technique for parsing context-free grammars.
- **Table Generation**: The code generates a set of parse tables (action and goto tables) that can be used to parse context-free grammars.
- **Conflict Resolution**: The code includes conflict resolution strategies to handle conflicts that arise during the parsing process.
- **Error Handling**: The code handles errors by returning false when an invalid action is encountered or when a reduce operation fails.
- **Duplicate Item Handling**: The code checks for duplicate items before adding them to the stack to prevent unnecessary processing.
- **Reduce State Handling**: The code updates the parse tables and stack when a reduce state is encountered, applying the production rules accordingly.

# Folder Structure
```sh
SLR_Parsing/ 
├── README.md
├── .mvn/ 
│   └── wrapper/ 
│       └── maven-wrapper.properties
├── mvnw
├── pom.xml
├── .gitattributes
├── mvnw.cmd
├── .gitignore
└── src/ 
    ├── test/ 
    │   └── java/ 
    │       └── com/ 
    │           └── compiler/ 
    │               └── slr_parser/ 
    │                   └── SlrParserApplicationTests.java
    └── main/ 
        ├── resources/ 
        │   └── application.properties
        └── java/ 
            └── com/ 
                └── compiler/ 
                    └── slr_parser/ 
                        ├── service/ 
                        │   └── ParserService.java
                        ├── SlrParserApplication.java
                        ├── controller/ 
                        │   └── ParserController.java
                        ├── util/ 
                        │   ├── FirstFollowGenerator.java
                        │   ├── TableGenerator.java
                        │   └── ParseString.java
                        └── model/ 
                            ├── ProductionRule.java
                            ├── ParsingTable.java
                            ├── Grammar.java
                            ├── LR0Item.java
                            ├── ParseCheckRequest.java
                            └── FirstFollow.java

18 directories, 21 files
```

Here's a detailed installation guide for the SLR Parsing project:

# Getting Started

Welcome to the SLR Parsing project! This guide will help you set up and run the project on your local machine.

## Prerequisites

Before installing the project, ensure that you have the following software installed:

1. **Node.js**: Install Node.js (version 14 or higher) from the official website: <https://nodejs.org/en/download/>
2. **Docker**: Install Docker Community Edition (version 20 or higher) from the official website: <https://www.docker.com/products/docker-desktop>
3. **Java Development Kit (JDK)**: Install JDK (version 11 or higher) for building and running Java-based applications
4. **Maven**: Install Maven (version 3 or higher) for building and managing dependencies

## Setup Instructions

1. **Clone the repository**: Clone the SLR Parsing project from GitHub using the following command:
```
git clone https://github.com/Eemayas/SLR_Parsing.git
```
2. **Navigate to the project directory**: Navigate into the cloned project directory:
```
cd SLR_Parsing/
```
3. **Install dependencies**: Install the required dependencies for Node.js and Maven using the following commands:
```
npm install
mvn clean install
```
4. **Configure environment variables**: Configure any necessary environment variables, such as `JAVA_HOME` and `M2_HOME`, to point to your installed JDK and Maven directories.

## Running the Project

1. **Build the project**: Build the SLR Parsing project using Maven:
```
mvn clean package
```
2. **Run the application**: Run the SLR Parsing application using the following command:
```
java -jar target/slr-parser-<version>.jar
```
Replace `<version>` with the actual version of your built JAR file.

## Troubleshooting

Common issues that may arise during installation include:

*   **Node.js installation**: If you encounter issues with Node.js installation, refer to the official documentation for troubleshooting: <https://nodejs.org/en/download/package-manager/>
*   **Docker setup**: For Docker-related issues, visit the official documentation for troubleshooting: <https://docs.docker.com/engine/install/>
*   **Maven configuration**: If Maven fails to build or install dependencies, ensure that your `settings.xml` file is correctly configured and points to the correct repository URLs.
*   **Java runtime errors**: Ensure that your JDK version meets the project's requirements (version 11 or higher).

To resolve these issues, follow the provided links for official documentation and troubleshooting guides.

That's it! You've successfully set up and installed the SLR Parsing project on your local machine.


# Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/Eemayas/SLR_Parsing/pulls)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/Eemayas/SLR_Parsing/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/Eemayas/SLR_Parsing/issues)**: Submit bugs found or log feature requests for SLR_Parsing.

### Contributing Guidelines

1. **Fork the Repository**:
    - Start by forking the project repository to your GitHub account.
2. **Clone the Repository**:
    - Clone your forked repository to your local machine using the command:
    ```sh
    git clone https://github.com/your-username/SLR_Parsing.git
    ```
    - Replace ``your-username`` with your GitHub username.
3. **Create a New Branch**:
    - Create a new branch for your changes using the command:
    ```sh
    git checkout -b your-branch-name
    ```
4. **Make Your Changes**:
    - Edit, add, or delete files as needed. Ensure your changes align with the project's contribution guidelines.
5. **Commit Your Changes**:
    - Stage your changes and commit them with a descriptive message:
      ```bash
      git add .
      git commit -m "Your descriptive message"
      ```
6. **Push Your Changes:**
    - Push your branch to your forked repository:
      ```bash
      git push origin your-branch-name
      ```
7. **Create a Pull Request (PR):**
    - Go to the original repository on GitHub and click “Compare & pull request.” Provide a clear description of the changes and submit the PR.

Once your PR is reviewed and approved, it will be merged into the main branch.
    


# Contributors

| Avatar | Contributor | GitHub Profile | No of Contributions |
|:--------:|:--------------:|:----------------:|:-------------------:|
| <img src='https://avatars.githubusercontent.com/u/100434825?v=4' width='40' height='40' style='border-radius:50%;'/> | Eemayas | [@Eemayas](https://github.com/Eemayas) | 3 |

        


# License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

