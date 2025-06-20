# Agile-BDD-Test-Automation-Framework

This project showcases a modular **BDD Test Automation Framework** built with **Java**, **TestNG**, **Cucumber**, **Gherkin**, **JSON**, and **XML**, developed using **IntelliJ IDEA**. It supports Agile testing practices and is structured for future CI/CD integration.

---

## Tools & Technologies

- **Java** – Programming language
- **IntelliJ IDEA** – IDE
- **TestNG** – Test framework
- **Cucumber** – BDD support
- **Gherkin** – Feature file syntax
- **JSON** – Test data configuration
- **XML** – `testng.xml` execution config
- **ARD (Agile Requirements Designer)** – Test model generation
- **Zephyr** – Test management
- **Jira** – Defect tracking & Agile board integration

---

## Project Structure

AgileTestAutomationFramework/


├── features/# Gherkin feature files
├── data/# JSON test data
├── config/# XML files (e.g., testng.xml)
├── src/
│   ├── main/java/
│   │   ├── steps/# Cucumber step definitions
│   │   └── utils/# Driver & support utilities
│   └── test/java/
│       └── runners/# TestNG test runner
├── pom.xml/# Maven project file (add dependencies)
└── README.md/# Project overview
