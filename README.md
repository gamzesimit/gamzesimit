<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FF8FAB&height=170&section=header&text=Gamze%20Simit&fontSize=46&fontColor=ffffff&fontAlignY=34&desc=QA%20Engineer%20·%20Accounting,%20Payments%20and%20Banking%20Software&descSize=15&descAlignY=54" width="100%" alt="Gamze Simit"/>

<img src="https://img.shields.io/badge/Austin,_TX-FB6F92?style=flat-square"/>
<a href="https://linkedin.com/in/gamzesimit"><img src="https://img.shields.io/badge/LinkedIn-FF8FAB?style=flat-square"/></a>
<a href="mailto:gamzenursimit@gmail.com"><img src="https://img.shields.io/badge/gamzenursimit@gmail.com-FF8FAB?style=flat-square"/></a>
<img src="https://img.shields.io/badge/Open_to_work-FFC2D1?style=flat-square&labelColor=FFC2D1"/>

</div>

<br>

### About

Six years inside financial systems before software: tax returns, payroll, bank
reconciliations, and compliance audits across more than 40 branches.

I build test automation, not just test cases. Frameworks in Java and Selenium on the
Page Object Model, API verification with Postman and REST Assured, SQL checks against
the database, and suites that run on every commit through GitHub Actions.

I test financial applications the way an accountant reads a ledger. I know what the
numbers are supposed to do, and I write the tests that prove whether the software
actually does it.

<br>

### Testing

`Manual` `Functional` `Regression` `Smoke` `Exploratory` `Black Box` `Boundary Value Analysis` `Equivalence Partitioning` `Database` `API` `Data Driven` `User Acceptance` `Risk Based` `Requirement Analysis` `Test Case Design` `Test Plans` `Defect Logging`

### Automation

`Selenium WebDriver` `Playwright` `Cypress` `Cucumber` `TestNG` `JUnit` `Page Object Model` `PageFactory` `BDD` `TDD` `Maven` `Apache POI` `k6`

### API and data

`Postman` `REST Assured` `Swagger` `SQL` `MySQL` `MySQL Workbench` `JDBC`

### Engineering

`Java` `TypeScript` `Gherkin` `Git` `GitHub Actions` `Jenkins` `Docker` `CI/CD` `Agile Scrum` `SDLC` `STLC` `JIRA`

### Financial domain

`General Ledger` `Accounts Payable` `Accounts Receivable` `Reconciliations` `Month End Close` `Sales Tax Filing` `Payroll` `Tax Returns` `Mortgage Origination` `Compliance Auditing` `Audit Trails` `QuickBooks` `PeopleSoft` `UltraTax` `Bloomberg Terminal` `Excel`

<br>

### Projects

**Automation**

**[parabank-test-automation](https://github.com/gamzesimit/parabank-test-automation)**
Playwright suite for a retail online banking application, written around the rules
that protect the balance. Twenty one tests on Chrome, Firefox and a phone profile,
page object model, running on every commit. Four defects found, two of them change
an account balance: a bill payment larger than the balance drives the account to
-1000.00, and a payment entered as a negative amount pays money in.
[Run report](https://gamzesimit.github.io/parabank-test-automation/)

**[banking-api-tests](https://github.com/gamzesimit/banking-api-tests)**
REST Assured and TestNG in Java with Maven. Thirty one checks over accounts,
customers, transfers, loans, transactions and error paths, with a response time
budget on every endpoint. Two k6 load profiles. Three defects, two critical: a
negative amount reverses the direction of a transfer, and the endpoint moves money
without asking who is calling.

**[banking-bdd-tests](https://github.com/gamzesimit/banking-bdd-tests)**
Cucumber and Gherkin over the same API, so the rule is readable by someone who does
not read Java. Ten scenarios, three tagged as known defects and excluded from the
default run.

**[ecommerce-checkout-tests](https://github.com/gamzesimit/ecommerce-checkout-tests)**
Playwright suite for a storefront, built around checkout arithmetic rather than
screens. Thirty two tests across desktop and phone, including accessibility checks.
Three defects, one of them an empty order the store confirms for 0.00.
[Run report](https://gamzesimit.github.io/ecommerce-checkout-tests/)

**[ui-edge-case-tests](https://github.com/gamzesimit/ui-edge-case-tests)**
Cypress over the browser behaviour that breaks automated tests: late content,
dialogs, frames, uploads, storage and layout at three widths. Forty six tests, no
fixed waits anywhere. Three defects, including a link that answers 404 while every
assertion about the element passes.
[Run report](https://gamzesimit.github.io/ui-edge-case-tests/)

**API and performance**

**[banking-postman-collection](https://github.com/gamzesimit/banking-postman-collection)**
Postman collection with the assertions written into the requests, run headless by
Newman on every commit. Seven requests, seventeen assertions. Balances asserted as
differences so the collection can be re-run against the same environment.

**[banking-jmeter-load](https://github.com/gamzesimit/banking-jmeter-load)**
Apache JMeter plan with the assertions inside it, so a fast wrong answer fails.
23,959 samples at 1,176 per second, zero errors, run on every commit.

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

**Software Engineering Bootcamp**
Manual and automated testing, Java, SQL, REST APIs, Agile delivery.

**Certifications**
Bloomberg Terminal: Equities, Fixed Income, Foreign Exchange, Commodities.
Mortgage Loan Originator examination.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FF8FAB&height=90&section=footer" width="100%"/>

</div>
