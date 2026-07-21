# Requirement Analysis Assignment — Online Book Store

## Project Overview
This repository contains my submission for the QA Internship **Requirement Analysis Assignment**. The goal of this project is to analyze the requirements of an Online Book Store system and translate business needs into structured documentation, including functional requirements, non-functional requirements, user stories, and acceptance criteria written in Gherkin syntax.

The full, formatted write-up is in the Word file:
📄 **[Requirement_Analysis_Online_Book_Store.docx](./Requirement_Analysis_Online_Book_Store.docx)**

This README gives a quick summary of what's inside that document.

## Learning Objectives
- Understanding requirement analysis for an e-commerce platform
- Identifying functional requirements
- Identifying non-functional requirements
- Writing user stories in structured format
- Writing acceptance criteria using Gherkin syntax
- Translating business requirements into testable scenarios
- Demonstrating clear and organized documentation practices

## Tasks Completed
1. Refined and documented user expectations for an online book shopping experience
2. Defined functional requirements of the system
3. Identified non-functional requirements related to performance, usability, and security
4. Wrote user stories describing interactions between users and the system
5. Defined acceptance criteria using Gherkin syntax
6. Organized all findings into a structured requirement analysis document (this repo)

## 1. Requirement Understanding
The Online Book Store allows users to:
- Browse books
- Search books
- View book details
- Add books to cart
- Purchase books online
- Manage user accounts

The business goal is to give customers a simple, reliable, and secure way to discover and buy books online, while giving the business tools to manage inventory, orders, and users. Full workflow description is in the Word doc, Section 2.

## 2. Functional Requirements (minimum 5 required — 10 provided)
| ID | Requirement |
|----|-------------|
| FR1 | User registration with email verification |
| FR2 | User login and logout |
| FR3 | Browse book catalog by category/author/new arrivals |
| FR4 | Search books by title, author, or category |
| FR5 | View detailed book information (price, description, stock, ratings) |
| FR6 | Add books to shopping cart |
| FR7 | Update quantity / remove items from cart |
| FR8 | Checkout and payment processing |
| FR9 | Order confirmation with order number |
| FR10 | View order history and status |

Full descriptions: Word doc, Section 3.

## 3. Non-Functional Requirements (minimum 2 required — 5 provided)
| ID | Requirement |
|----|-------------|
| NFR1 | Performance — pages load within 3 seconds |
| NFR2 | Security — encrypted data in transit/at rest, HTTPS checkout |
| NFR3 | Availability — 99.5% uptime |
| NFR4 | Usability — intuitive on desktop and mobile |
| NFR5 | Scalability — supports 5x peak concurrent users |

Full descriptions: Word doc, Section 4.

## 4. User Stories
10 user stories in the format **"As a ... I want ... so that ..."** covering registration, login, browsing, searching, viewing details, cart management, checkout, and order tracking.
Full list: Word doc, Section 5.

## 5. Acceptance Criteria — Gherkin Syntax (minimum 5 required — 7 provided)
Scenarios included:
1. User registration with valid details
2. Successful login
3. Search for a book
4. View book details
5. Add a book to the cart
6. Remove a book from the cart
7. Successful checkout and payment

Each scenario follows `Given / When / Then` (and `And` where needed). Full scenarios: Word doc, Section 6.

## 6. Sprint Planning
| Sprint | Focus Area | Key Deliverables |
|--------|-----------|-------------------|
| Sprint 1 | Account & Access | Registration, login/authentication, account management |
| Sprint 2 | Catalog Browsing | Browse catalog, search, view book details |
| Sprint 3 | Cart & Checkout | Add/remove cart items, checkout, payment |
| Sprint 4 | Order & Polish | Order confirmation, order history, performance & security hardening |

Full table: Word doc, Section 7.

## Tools & Technologies
- Gherkin (Given/When/Then syntax)
- Manual requirement analysis techniques

## Repository Contents
```
.
├── README.md
└── Requirement_Analysis_Online_Book_Store.docx
└── Requirement_Analysis_Online_Book_Store.pdf
└── Requirement_Analysis_Online_Book_Store.md 


 Author
[Muhammad Muntasir] — QA Internship Candidate
