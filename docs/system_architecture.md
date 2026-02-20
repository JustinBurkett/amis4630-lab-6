# System Architecture Diagram and User Needs

<img width="1334" height="691" alt="Buckeye Marketplace Architecture" src="https://github.com/user-attachments/assets/2f6a8d05-e1cc-42b2-99de-4c0b93118aef" />

Based on the architecture shown above, our technology choices solve the following user needs identified in Milestone 1:

### Trust and Safety (The Parent)
* **Decision:** We are using a .NET API Service with a dedicated Identity & Auth Service.
* **Connection:** This ensures that every user is verified and their profile data is handled securely, which provides the safe environment parents require for campus transactions.

### Inventory Management (The Student)
* **Decision:** We are utilizing React for the Product Catalog UI and Shopping Cart UI.
* **Connection:** This allows students to manage multiple listings with real-time updates. The component-based nature of React makes handling complex states like the shopping cart efficient and interactive.

### Reliable and Structured Discovery (The Alumni)
* **Decision:** We are using Azure SQL Database connected via Entity Framework.
* **Connection:** Because our data (Users, Listings, Orders) is highly structured and relational, this database ensures that Alumni can perform precise searches across categories with 100% data integrity.
