Flipkart Web Automation
📌 Project Overview

This project is an end-to-end automation testing framework designed for automating Flipkart’s web application. It uses Selenium WebDriver along with TestNG and Cucumber for writing and managing test cases, integrated with Maven for build management and Extent Reports for detailed reporting.

The framework supports cross-browser testing and integrates with BrowserStack for cloud-based execution.

🚀 Features

✅ Page Object Model (POM): Maintains reusable, clean, and maintainable code.

✅ Cross-Browser Testing: Supports Chrome, Firefox, and cloud execution via BrowserStack.

✅ Data-Driven Testing: Uses Excel (Xls_Reader) and property files for test data.

✅ TestNG Framework: Parallel execution, annotations, retry logic, and listeners.

✅ Cucumber BDD (Optional): Human-readable test scenarios for better collaboration.

✅ Extent Reports: Generates interactive HTML reports for test results.

✅ Reusable Utilities: Includes helper classes for properties, browsers, and data handling.

🛠️ Tools & Technologies

Programming Language: Java

Automation Tool: Selenium WebDriver

Test Frameworks: TestNG, Cucumber

Build Tool: Maven / Gradle (both configurations present)

Reporting: ExtentReports

Cloud Execution: BrowserStack

IDE: IntelliJ IDEA / Eclipse

📂 Project Structure
FlipkartWebAutomation
│── pom.xml                  # Maven build file
│── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── driver/      # Driver initialization & BrowserStack setup
│   │   │   ├── pages/       # Page Object Model classes (LoginPage, HomePage, etc.)
│   │   │   ├── utils/       # Utilities (Property reader, Browser configs)
│   │   │   └── utilityClass # Excel Reader, Helpers
│   │   └── resources/       # Config files (properties)
│   └── test/
│       ├── java/
│       │   ├── testBase/    # Base test setup
│       │   ├── testCases/   # Test cases (SearchProductTestCases, etc.)
│       │   ├── listener/    # Retry logic, activity capture
│       │   └── report/      # Extent report manager
│       └── resources/       # Test data & feature files
│── reports/                 # HTML Test Reports

⚡ How to Run the Tests
1️⃣ Clone the Repo
git clone https://github.com/Anshbagwar/FlipkartWebAutomation.git
cd FlipkartWebAutomation

2️⃣ Install Dependencies
mvn clean install

3️⃣ Run Test Cases
mvn test

4️⃣ View Reports

Reports are generated under /reports/ExtentReportResults.html

Open in a browser to see test results with screenshots.

📋 Example Test Cases

Login Test: Verify user login with valid credentials.

Product Search: Validate that search functionality returns correct results.

Product Details: Verify product details page (price, title, description).

Add to Cart: Ensure items can be added to the cart.

Guest Checkout: Validate flow for guest users.

📊 Pros & Cons
✅ Pros

Scalable framework with modular design.

Supports cloud execution & parallel runs.

Extent Reports for detailed results.

Data-driven + BDD support.

❌ Cons

Slightly complex for beginners.

Multiple build tools (Maven & Gradle) may confuse.

Dependency on BrowserStack for full cross-browser coverage.

📄 Resume Highlights (Add as Points)

Developed an automation framework for Flipkart web app using Selenium, TestNG, and Maven.

Implemented Page Object Model (POM) and data-driven testing for maintainability.

Integrated Extent Reports for detailed test execution insights.

Configured BrowserStack for cross-browser/cloud test execution.

👤 Author

Ansh Bagwar
📧 anshbagwarsai@gmail.com
🌐 https://www.linkedin.com/in/ansh-bagwar-339b42251/
