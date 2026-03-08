# 🚀 QE Automation (Selenium + Cucumber + TestNG)

![Java](https://img.shields.io/badge/Java-20-blue?logo=openjdk)
![Selenium](https://img.shields.io/badge/Selenium-4.x-43B02A?logo=selenium)
![Cucumber](https://img.shields.io/badge/Cucumber-BDD-23D96C?logo=cucumber)
![CI](https://img.shields.io/badge/CI-Windows-2088FF?logo=githubactions)

Modular UI test automation framework using **Java, Selenium, Cucumber, and TestNG**.

## 📦 Modules
- **Framework**: reusable core (driver, wrappers, hooks, config, logging, reporting)
- **AssessmentProj**: executable tests (features, step definitions, page objects, runner)

## ✨ Highlights
- Maven multi-module setup
- Page Object Model (POM)
- Cucumber + TestNG parallel execution
- Extent + Cucumber reports
- GitHub Actions Windows CI

## ✅ Prerequisites
- Java 20
- Maven 3.6+
- Chrome

## ⚡ Quick Start
```sh
git clone <your-repository-url>
cd QE-Automation
mvn clean verify
```

## ▶️ Run Tests
```sh
mvn clean test -fae
```

With runtime options:
```sh
mvn clean test -fae -DBrowserType=CHROME -DBrowser=CHROME -DHeadless=true
```

## 📊 Output
- `Reports/ExecutionReport <timestamp>/ExtentReport_<timestamp>.html`
- `AssessmentProj/target/cucumber-reports/`
- `Logs/`

## 🔁 CI
- `.github/workflows/WinBuildCI.yml`

## 📄 License
MIT License
