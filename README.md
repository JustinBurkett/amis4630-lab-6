# amis4630-spring26-burkett
AMIS 4630 Buckeye Marketplace Project

# Buckeye Marketplace - Deliverable 3

## Table of Contents
1. [Business System Summary](#1-business-system-summary)
2. [Feature Prioritization](#2-feature-prioritization)
3. [Architecture Decisions](#3-architecture-decisions)
4. [Documentation Folder](#4-documentation-folder)

---

## 1. Business System Summary
The Buckeye Marketplace is a platform designed for the Ohio State community to trade goods safely. 
* **For the Student:** The **Product Listing** entity allows them to manage multiple active sales with clear ownership.
* **For the Parent:** The **Profile** entity provides a transparent campus identity for secure transactions.
* **For the Alumni:** The **Product-Category** entity enables structured browsing to find specific gear efficiently.

## 2. Feature Prioritization
Based on our persona needs, the following features are prioritized for the initial release:

| Feature | Priority | Persona Goal |
| :--- | :--- | :--- |
| User Profile Management | Must-Have | Safety and Trust (Parent) |
| Product Listings | Must-Have | Inventory Management (Student) |
| Category-Based Search | Must-Have | Efficient Discovery (Alumni) |
| Shopping Cart & Orders | Must-Have | Secure Transactions (All) | 

I have also assigned priority labels to each feature—categorized as Must-Have, Should-Have, or Could-Have—to ensure the development roadmap focuses first on the core security and transaction needs of our Students, Parents, and Alumni.

## 3. Architecture Decisions
We have selected a robust "Enterprise Stack" to ensure security and scalability:
* **Frontend:** **React** for a component-based, interactive user interface.
* **Backend:** **.NET (C#)** for secure, type-safe server logic and transactions.
* **Database:** **Azure SQL** to maintain relational integrity between users and products.

## 4. Documentation Folder
Detailed design records can be found in the `/docs` folder:
* [ERD & Persona Logic](./docs/design_decisions.md)
* [Atomic Design Component Hierarchy](./docs/component_architecture.md)
* [Full ADR Records](./docs/ADR.md)
* [System Architecture Diagram](./docs/system_architecture.md)
