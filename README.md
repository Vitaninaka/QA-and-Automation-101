# QA and Automation 101

In this course students will learn the basic theory behind software quality
assurance and test automation. More importantly they will learn how to think
like testers and analyze a given problem from various angles, often without
complete information available.

The theory lessons include exerices like writing a bug report or writing
test cases and test plans, sometimes in hypothetical environments, sometimes
using real software when possible.

In order to gain the maximum benefit of this course please clone this repo
and write down your answers to the exercises, links to bug reports and test
plans. These can be later shown to prospect employers.

## Course Program

### Lessons -2, -1, 0 - Java 101 Refresh course

Please see https://github.com/HackBulgaria/Programming101-Java

### Lesson 1 - [QA Fundamentals](/lesson01/)

This is an introduction to software testing in general. The industry uses the
terms testing, quality assurance and quality engineering more or less as
synonyms but there is a difference behind them and we will explain that
before going further. We will briefly cover the following topics using
practical examples and exercises.

* Definition of testing, QA and QE
* Why we need testing
* How do we know when to stop
* Tester vs. developer
* The psychology of testing
* Different types of testing
* Testing techniques


### Lesson 2 - [Software Development Lifecycle](/lesson02/)

Introduction to software development lifecycle and how it relates to testing
activities.

* Waterfall model
* Agile models
* QA's involvement in both


### Lesson 2 - [Bug Tracking](/lesson02/)

*"If it's not in Bugzilla it's not a bug!"*

* Generic definition
* How to write a good bug report
* Practicing writing and analyzing bug reports



### Lesson 3 - [Test Case Management](/lesson03/)

*“If it is not in the TCMS then we don't test it!”*

* What is test management
* Generic definitions of
 * Test Case
 * Test Plan
 * Test Run aka Test Execution
* IEEE test plan structure
* Positive and negative tests
* Practice with Nitrate TCMS


### Lesson 4 - [Testing Fedora 24 Changes](/lesson04/)

This is a practice only lesson. Students will be testing
new features proposed for the upcoming Fedora 24 release.


### Lesson 5 - [Unit Testing and Continuous Integration](/lesson05/)

Unit testing and CI are traditionally developer oriented activities
but QA is increasingly starting to take part in both of them.

* What is unit testing
* Fakes, stubs, mocks and doubles
* Introduction to JUnit
* Continuous Integration and code coverage


### Lesson 6 - [Writing JUnit tests for Apache Commons](/lesson06/)

This is a practive only lesson. Students will be writing
JUnit tests for popular Apache Commons components and inspecting
changes in code coverage.

### Lesson 7 - [Integration Testing with Selenium](/lesson07/)

Selenium is a popular test automation framework for web based applications.
In this lesson we learn about how test cases and software need to be written in
order to be automated and explore the Selenium IDE.

* Theory of test automation
* What is automatable software
* Introduction to Selenium


### Lesson 8 - [Writing Selenium tests for Mozilla Add-ons website Pt.1](/lesson08/)

This is a practice only lesson. Students will be writing
automated Selenium tests for http://addons.mozilla.org.

### Lesson 9 - [Writing Selenium tests for Mozilla Add-ons website Pt.2](/lesson08/)

This is continuation of the previous practice only lesson.

### Lesson 10 - [Introduction to performance testing](/lesson10/)

Introduction to performance testing targeted mostly towards discussions and understanding
what performance testing is. The lesson explores several examples of basic performace
testing and includes a practical exercise.

* Short theory with examples
* Designing performance test strategy for GitHub

### Lesson 11 - [How to find 1000 bugs in 30 minutes](/lesson11/)

In every suffiently large software system even the smallest change can affect multiple
components and lead to a big number of bugs. The lesson explores several examples of
such bugs and gives the students the background to start finding bugs by the hundreds.

* Introduction to mass scale exploratory testing
* Let's find at least 100 bugs in Fedora 24
