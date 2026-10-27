<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FF8FAB&height=170&section=header&text=Gamze%20Simit&fontSize=46&fontColor=ffffff&fontAlignY=34&desc=QA%20Engineer%20·%20Accounting,%20Payments%20and%20Banking%20Software&descSize=15&descAlignY=54" width="100%" alt="Gamze Simit"/>

<img src="https://img.shields.io/badge/Austin,_TX-C9184A?style=for-the-badge"/>
<a href="https://linkedin.com/in/gamzesimit"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:gamzenursimit@gmail.com"><img src="https://img.shields.io/badge/gamzenursimit@gmail.com-C9184A?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Open_to_work-2E7D32?style=for-the-badge"/>

</div>

<br>

### About

Nine years inside financial systems before software: tax returns, payroll, bank
reconciliations, and compliance audits across more than 40 branches.

I build test automation, not just test cases. Playwright with TypeScript, Selenium with
Java and Cypress, all on the Page Object Model; API verification with REST Assured and
Postman; load runs in JMeter; SQL checks against the database; and suites that run on
every commit through GitHub Actions.

I test financial applications the way an accountant reads a ledger. I know what the
numbers are supposed to do, and I write the tests that prove whether the software
actually does it.

<br>

### Automation

`Playwright` `TypeScript` `Selenium WebDriver` `Java` `Cypress` `JavaScript` `TestNG` `Cucumber / BDD` `Page Object Model`

### API, performance and data

`REST Assured` `Postman / Newman` `Apache JMeter` `SQL` `MySQL` `Accessibility checks (axe)`

### Delivery

`GitHub Actions` `Docker` `Maven` `Git` `JIRA` `Agile Scrum`

### Testing practice

`Risk-Based Testing` `Test Plans` `Test Case Design` `Traceability Matrix` `Boundary Analysis` `Regression` `Defect Reporting`

### Financial domain

`General Ledger` `AP / AR` `Reconciliations` `Month End Close` `Payroll` `Tax Returns` `Mortgage Origination` `Compliance Auditing` `QuickBooks` `PeopleSoft` `Bloomberg Terminal`

<br>

### Projects

**Browser automation**

**[ecommerce-checkout-tests](https://github.com/gamzesimit/ecommerce-checkout-tests)**
Playwright and TypeScript for a storefront, built around checkout arithmetic rather
than screens. Thirty two tests on desktop and a phone profile, including
accessibility checks. Three defects, one of them an empty cart checked out into a
confirmed order.

**[parabank-test-automation](https://github.com/gamzesimit/parabank-test-automation)**
Playwright and TypeScript for a retail online banking application, on Chrome,
Firefox and an iPhone profile. Twenty one tests around the rules that protect the
balance. Four defects, two of them change an account balance. The same application
is tested with Selenium below, so the two tools can be compared on one target.

**[parabank-selenium-tests](https://github.com/gamzesimit/parabank-selenium-tests)**
Selenium WebDriver in Java with TestNG and Maven, on the Page Object Model with
PageFactory, for a retail online banking application. Twenty tests, with sign-in
cases and amounts read from Excel through Apache POI. Four defects found through
the browser, two of them on the transfer screen: a negative amount moves the money
backwards, and a transfer larger than the balance drives the account to -1000.00.

**[ui-edge-case-tests](https://github.com/gamzesimit/ui-edge-case-tests)**
Cypress over the browser behaviour that breaks automated tests: late content,
dialogs, frames, uploads, storage and layout at three widths. Forty six tests with
no fixed waits. Three defects.

**API and performance**

**[banking-api-tests](https://github.com/gamzesimit/banking-api-tests)**
REST Assured and TestNG in Java with Maven. Thirty one checks over accounts,
customers, transfers, loans, transactions and error paths, with a response time
budget on every endpoint. Three defects, two critical: a negative amount reverses
the direction of a transfer, and the endpoint moves money without asking who is
calling.

**[banking-bdd-tests](https://github.com/gamzesimit/banking-bdd-tests)**
Cucumber and Gherkin over the same API, so the rule is readable by someone who does
not read Java. Ten scenarios, three tagged as known defects and excluded from the
default run.

**[banking-postman-collection](https://github.com/gamzesimit/banking-postman-collection)**
Postman collection with the assertions written into the requests, run headless by
Newman on every commit. Seven requests, seventeen assertions. Balances asserted as
differences so the collection can be re-run against the same environment.

**[banking-jmeter-load](https://github.com/gamzesimit/banking-jmeter-load)**
Apache JMeter load plan for the same banking API, run headless on every commit with
the assertions inside the plan, so a fast wrong answer still fails.

**Written testing and data**

**[banking-test-documentation](https://github.com/gamzesimit/banking-test-documentation)**
The part that comes before automation: test plans with entry and exit criteria and
a risk table, twelve executable test cases, eleven requirements, a traceability
matrix tying each one to a manual case and an automated test, and defect reports.

**[sql-for-testers](https://github.com/gamzesimit/sql-for-testers)**
Queries that check an accounting database is telling the truth: invoice arithmetic,
referential integrity, data quality, duplicates and reconciliation. Written so a
clean database returns no rows, and four of them proved against a database with a
fault inserted.

**[accounting-defect-study](https://github.com/gamzesimit/accounting-defect-study)**
Defect study of an open source accounting platform. Two reproducible defects with
one root cause, traced through the source: hidden outbound calls that fail silently.
On a fresh install no record of any kind can be created.

### Background

**The University of Tennessee, Knoxville**
B.S. Business Administration. Major: Accounting, Collateral in Finance. GPA 3.5/4.0.

**Software Engineering Bootcamp, NeoTech Academy**
April 2024 to March 2025. Manual and automated testing, Java, SQL, REST APIs, Agile delivery.

**Software Testing Bootcamp, TechPro Education**
August 2023 to December 2023.

**Certifications**
Bloomberg Terminal: Equities, Fixed Income, Foreign Exchange, Commodities.
Mortgage Loan Originator examination.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FF8FAB&height=90&section=footer" width="100%"/>

</div>
