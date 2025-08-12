🔐 TestNG Reports – Selenium Java
--------------

📌 Overview

This project is a Java TestNG-based automation suite using Selenium WebDriver.

It demonstrates running simple browser tests and generating TestNG reports through multiple methods, including emailable-report.html, index.html dashboard, and Reporter.log outputs.

Both test cases pass successfully, showcasing clean report generation.


--------------

✨ Features

✅ Pass status for all tests (DemoA and DemoB)

🔍 Automated browser interaction with FirefoxDriver

📑 TestNG reports generation in multiple formats:

  - emailable-report.html

  - index.html (TestNG dashboard)

  - Reporter.log() output for detailed logs


--------------

📂 Project Structure

📁 src

.gitignore                # Files/folders ignored by git

├── 📄 DemoA.java         # Test case opening Google and entering "Hi"

├── 📄 DemoB.java         # Test case opening Google and entering "Bye"

📄 DemoTestNG.xml         # TestNG test suite configuration

📄 LICENSE                # MIT License

📄 README.md              # Project documentation

📁 reports               # Generated reports

├── [📄 emailable-report.html](file:///D:/Eclipse%20IDE%20JAva%20Testing/TestNG/1.1/test-output/emailable-report.html)

└── [📄 index.html](file:///D:/Eclipse%20IDE%20JAva%20Testing/TestNG/1.1/test-output/index.html)

📄 pom.xml                # Maven dependencies and build configuration

--------------

🛠️ Technologies Used

- Java 8+

- Selenium WebDriver

- TestNG Framework

- Maven (for dependency management)

- Eclipse / IntelliJ IDEA (recommended IDEs)


--------------

📦 Installation & Running Tests

1. Clone the repository:

  - git clone [ReportsTestNG](https://github.com/AhmedElian/ReportsTestNG.git)
2. Open the project in your IDE (Eclipse/IntelliJ/VS Code).

3. Run the TestNG suite:

  - Option 1: Run testng.xml suite file directly from IDE

  - Option 2: Use Maven from the command line:

--------------

📊 Test Data Coverage

Test Class   | Action   | Expected             | Result	       | Status

DemoA	       | Open     | Google, enter "Hi"	 | Text entered	 | ✅ Pass

DemoB	       | Open     | Google, enter "Bye"  | Text entered	 | ✅ Pass

--------------

⚠️ Disclaimer

This project is for educational purposes only and demonstrates how to generate TestNG reports.

It is not intended for production use or real test environments.

--------------
⭐ If you find this project helpful, please consider giving it a star on GitHub!
--------------
