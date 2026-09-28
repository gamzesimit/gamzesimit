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

**[parabank-test-automation](https://github.com/gamzesimit/parabank-test-automation)**
Playwright suite for a retail online banking application, written around the rules
that protect the balance rather than around the screens. Twenty one tests, page object model,
running on Chrome, Firefox and a phone profile through GitHub Actions against the
application in a container. Four defects found, two of them change an account balance: a bill payment
larger than the balance is accepted and drives the account to -1000.00, and a payment
entered as a negative amount pays money into the account instead of out of it.

**[accounting-defect-study](https://github.com/gamzesimit/accounting-defect-study)**
Defect study of an open source accounting platform. Two reproducible defects with one
root cause: hidden outbound calls that fail silently. On a fresh install no record of
any kind can be created, and the screens redirect with no message. Traced to a
middleware that asks a vendor service for plan limits and treats no answer as no
permission.

**[banking-api-tests](https://github.com/gamzesimit/banking-api-tests)**
REST Assured and TestNG against the API of the same banking application, in Java
with Maven, plus a k6 load profile with thresholds agreed before the run. Twenty two checks. Three
defects at the API surface, two of them critical: a transfer with a negative
amount reverses the direction of the money, and the transfer endpoint moves money
without asking who is calling.

**[ecommerce-checkout-tests](https://github.com/gamzesimit/ecommerce-checkout-tests)**
Playwright suite for a storefront, built around checkout arithmetic rather than
screens. Twenty five tests across a desktop and a phone profile: item total against the
lines, tax at the stated rate, total against its parts, all four catalogue sort
orders verified rather than assumed, and the cart covered end to end. Three
defects, including an empty cart that walks through checkout and is confirmed.

<br>

**[ui-edge-case-tests](https://github.com/gamzesimit/ui-edge-case-tests)**
Cypress suite over the browser behaviour that breaks automated tests: content
that arrives late, alerts, frames, new windows, file upload and download, and
tables that claim to sort. Thirty five tests, no fixed pauses anywhere. Three
defects reported, including a money column that had to be checked as numbers
rather than as text and a link that answers 404 while every assertion about the
element passes.

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
