 #Online Banking System
 
## Document:
System Requirement Specification Document

## Title:
System Requirement Specification for Online Banking System

## Team:
Direct Customer, Architect, Business Analyst, Quality Assurance Team, System Analyst.

## Objective (Purpose):
OBS intends to provide several banking services to individuals and organisations. The purpose of the project is to build an application program to reduce the manual work for managing the accounts, internet banking, customer, transaction. It tracks all the details about the transaction, balance, statement.

## Scope:
This system allows consumers to open new bank account from any remote location via an internet gateway and digital verification, in less time and zero paperwork.
Customers will be able to make transactions 24*7, and review the history of transactions made.
Banking services for corporate clients are also provided through this system.

## Definitions:
OBS - Online Banking System
QA - Quality Assurance
KPI- Key Performance Index
BOD- Board of Director

# Functional Requirements:

## New account opening:
- Any individual customer, interested in opening a new bank account can visit the website to fill up a registration form.
- Once the registration details are submitted, it is sent for approval, to the banking administration.
- Upon getting the approval, the account will be successfully setup, or else the new account will not be generated.

## Existing account login:
- All existing individual/corporate customers will be able to access their accounts using the credentials provided to them.
- Customers will be able to make transfer of funds by providing account number of the beneficiary.
- A customer can also view his account balance along with his transaction history.
- The functionality of making updates on a customer’s profile is also provided.

## Bank employee login:
- An employee of bank with administrative privileges has access to account details of all the customers at bank.
- The bank employee also has the responsibility to approve/reject any new request of bank account creation.

## BOD login:
- BOD's upon login are provided with daily/monthly/quaterly/yearly updates of revenue generated based on the transactions cleared on each day.

# Non Functional Requirements:

### Atomicity
The entire transaction takes place at once or doesn’t happen at all. 
There is no midway i.e. transactions do not occur partially. 
Each transaction is considered as one unit and either runs to completion or is not executed at all.

### Consistency
The integrity constraints are maintained so that the database is consistent before and after the transaction. 
It refers to the correctness of a database.

### Security
System will automatically log of all customers after some time due to inactiveness.
System will block operations for inactive customers and would redirect for authentication.

### Reliability
The system will backup transaction and customer data on regular basis and recover in short time duration to keep system operational.
Continuous updates are maintained, continuous administration is done to keep system operational.
During peak hours system will maintain same user experience by managing load balancing.
