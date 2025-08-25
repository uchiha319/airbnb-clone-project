# airbnb-clone-project
This project is a full-stack Airbnb clone built to replicate the core functionality of the popular vacation rental platform. Users can browse listings, book stays, and manage their own properties through a sleek, responsive interface.

#Team Roles
- Product Owner: Represents the client’s vision, prioritizes features, and ensures the product meets business goals.
- Project Manager: Oversees timelines, resources, and communication between stakeholders and the team.
- Business Analyst: Translates business needs into technical requirements and helps define project scope.
- UI/UX Designer: Crafts user interfaces and experiences that are intuitive and aligned with user expectations.
- Software Architect: Designs the system’s high-level structure and ensures scalability and maintainability.
- Software Developers: Write and maintain the codebase, turning designs and requirements into working software.
- Quality Assurance Engineers: Test the product to ensure it meets quality standards and is bug-free.
- Test Automation Engineers: Build automated testing frameworks to speed up and standardize QA processes.
- DevOps Engineers: Handle deployment, infrastructure, and continuous integration/delivery pipelines.

#Technology Stack
• Django (Python Web Framework)A high-level framework for building secure, scalable web applications quickly.
- Comes with built-in features like ORM, admin panel, authentication, and routing.
- Ideal for enterprise platforms, REST/GraphQL APIs, and AI-enhanced backends.

• MySQL (Relational Database)A robust, open-source database system for storing structured data.
- Supports complex queries, joins, and transactions — perfect for analytics and reporting.
- Integrates seamlessly with Django’s ORM for efficient data handling.
  
 • GraphQL (API Query Language) A flexible alternative to REST that lets clients request exactly the data they need.

 #Database Design 
- Reduces over-fetching and under-fetching, improving performance for mobile and web apps.
- Works well with Django via libraries like Graphene, enabling dynamic, schema-driven APIs.

#Database Design
. Users
- Name
- Email
- Id 

. Properties
- User Id
- Location
- Description

. Bookings
- Status
- start date
- end date

. Reviews
- user-id
- rating
- comment

 . Payments 
 - booking_id
 - method
 - amount
    
#Feature Breakdown

. User Management
Handles user registration, login, and profile management. This feature ensures secure access and personalized experiences for both hosts and guests, using role-based permissions to differentiate functionality.

. Property Management
Allows hosts to list properties with details like location, pricing, and availability. It forms the backbone of the platform, enabling dynamic property listings and updates.

. Booking System
Enables guests to book available properties for specific dates. It includes conflict checks, booking status updates, and calendar integration to streamline the reservation process.

. Payment Integration
Processes payments securely for confirmed bookings. This feature supports multiple payment methods and ensures transaction reliability, enhancing trust between users.

. Review & Rating System
Lets guests leave feedback on properties after their stay. Reviews help maintain quality standards and guide future guests in making informed decisions.

. Search & Filter
Provides users with tools to search properties by location, price, amenities, and availability. It improves user experience by helping them find the most suitable options quickly.


