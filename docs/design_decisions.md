# ERD and Persona Logic

## Entity Relationship Diagram
<img width="2122" height="700" alt="ERD Buckeye Marketplace" src="https://github.com/user-attachments/assets/3eb4c8f6-f5f1-461f-87f3-0f0fd385d540" />

## Persona Connection Logic
Our schema design directly supports the specialized needs of our three core personas:

* **The Student:** The **Product Listing** entity branched off the **User** with a 1:M relationship allows them to manage multiple active sales while maintaining clear ownership of their inventory.

* **The Parent:** Supported by the **Profile** entity, which allows users to maintain a transparent campus identity and public-facing persona, providing the security needed for safe transactions.

* **The Alumni:** Can navigate the marketplace efficiently thanks to the **Product-Category** entity; this allows for the structured browsing required to find specific gear across the database's many listings.
