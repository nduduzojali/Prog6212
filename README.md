# Prog6212
System Overview
The Contract Monthly Claim System (CMCS) is a comprehensive .NET web-based application designed to streamline the process of submitting and approving monthly claims for independent contractor lecturers. This system addresses the complex administrative challenges faced by educational institutions in managing contractor payments, providing a user-centric design with seamless integration of essential features.
Design Choices Rationale
Architecture Decision: The system utilizes a three-tier architecture (Presentation, Business Logic, Data Access) implemented using ASP.NET Core MVC pattern. This choice ensures separation of concerns, maintainability, and scalability. The Model-View-Controller pattern provides clean separation between user interface, business rules, and data management.
Database Design: A relational database approach using Entity Framework Core ensures data integrity through normalized tables with appropriate foreign key relationships. The design supports complex claim calculations based on hours worked and corresponding hourly rates, with comprehensive audit trails for accountability.
User Interface Strategy: The GUI employs responsive web design principles using Bootstrap framework, ensuring accessibility across devices. The interface prioritizes user experience with intuitive navigation, clear status indicators, and streamlined workflows that reduce administrative burden on both lecturers and administrators.





Database Structure Explanation
The database schema consists of seven core entities: Users (handling authentication and roles), Lecturers (contractor-specific information), Claims (main transaction records), Documents (supporting file attachments), Subjects (course information), ClaimStatus (workflow states), and AuditLog (tracking all system changes). Each entity serves specific business requirements while maintaining referential integrity through carefully designed relationships.
