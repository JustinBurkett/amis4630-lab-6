# Architecture Decision Records

## ADR 01: Frontend Framework - React

* Decision: We are using React for the user interface.

* Rationale: Reacts component-based architecture allows us to build a highly interactive marketplace that feels seamless for students browsing on the go. Its vast ecosystem ensures we can easily integrate OSU-themed styling and handle complex states like the Shopping Cart efficiently.

* Status: Accepted.

## ADR 02: Backend Framework - .NET (C#)

* Decision: We are using .NET for the server-side logic.

* Rationale: .NET provides a robust, type-safe environment that is ideal for handling financial transactions (Orders) and sensitive user data (Profiles). Its built-in security features help maintain the "Trust and Safety" requirement essential for a campus environment.

* Status: Accepted.

## ADR 03: Database - Azure SQL

* Decision: We are using Azure SQL as our relational database.

* Rationale: Since our data is highly structured (linking Users to Listings and Orders), a relational database is necessary to maintain data integrity. Azure SQL offers seamless scaling and cloud hosting, ensuring the marketplace remains performant during high-traffic periods like "Move-in Week".

* Status: Accepted.

## AI Tool Usage: Documentation- Tool: Gemini 3 Flash

* Technology Justification: I used the AI to research the specific benefits of the React/.NET/SQL stack for e-commerce. The AI highlighted that this "Enterprise Stack" is preferred for its scalability and security, which directly supports our persona-based goals for a safe marketplace. 

* Standardization: I prompted the AI to help format these decisions into official Architecture Decision Records (ADRs) to ensure the documentation meets professional industry standards.
