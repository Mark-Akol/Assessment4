
### Book Profile Feature Tests: Add and Remove Functionality
This project implements automated feature tests for adding and removing books from a user profile using Java, TestNG, and Selenium WebDriver.

#### Project Structure:

Demoqa.java: This class represents the Demoqa profile page and provides methods for interacting with its elements, such as adding and checking for the presence of books.
Demoqa.java: This class contains the actual test cases using TestNG annotations. 

#### Running the Tests:

##### Prerequisites: Ensure you have Java, Maven, and the required libraries (Selenium WebDriver, TestNG) set up in your development environment.
Build the project: Run mvn package in your terminal to compile and package the tests.
Execute the tests: Use a test runner like testng to execute the tests. You can run all tests using testng or individual tests by specifying their class and method names.

#### Explanation:

The Demoqae class follows the encapsulation of page elements and interactions. This improves code maintainability and reusability.
The Demoqa class uses TestNG annotations like @Test to define test cases.
The addBookToProfile test case demonstrates adding a book and verifying its presence using the isBookPresent method.
The removeBookFromProfile test case depends on the successful addition of the book in the previous test and then verifies its removal.
