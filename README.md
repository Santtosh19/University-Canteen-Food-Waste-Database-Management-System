# University-Canteen-Food-Waste-Database-Management-System
This project involves the development of a comprehensive database management system (DBMS) for managing and analyzing food waste data in university canteens. The system is designed to help canteen management monitor food waste, optimize inventory management, and reduce costs while promoting sustainable practices. The project also integrates various modules such as financial assessment, inventory management, and analytical tools to provide a holistic approach to managing food waste.


## Key Features:

1. Food Waste Collection Module: Tracks and collects real-time data on food waste, including type, quantity, date, and reason for waste.

2. Inventory Management Module: Manages inventory levels, tracks expiry dates, and optimizes food storage to prevent overstocking and waste.

3. Financial Assessment Module: Categorizes expenses, predicts budgets, and estimates losses due to food waste, ensuring transparency and accountability.

4. Analytical Module: Analyzes trends in food waste generation, predicts future waste, and estimates carbon emissions associated with food waste.

### Tools and Technologies:

~Database: Oracle APEX for database management and SQL for querying.

~ERD Notation: Crow’s Foot Notation for designing the Entity Relationship Diagrams (ERDs) using
Drawio: https://app.diagrams.net/

~Programming: SQL for database creation, triggers, and sequences.


### How to Run:
Requirements:

Oracle APEX environment set up.
SQL scripts for creating tables, triggers, and sequences.

### Running the System:

Execute the SQL scripts provided to create the necessary tables, triggers, and sequences in the Oracle APEX environment.
Use Oracle APEX to access the front-end of the system, where users can interact with the different modules (Food Waste Collection, Inventory Management, Financial Assessment, Analytical).
Using the Modules:

1.Food Waste Collection: Users can input data related to food waste, categorized by food type and stall.

2.Inventory Management: Monitor and manage food inventory, track expiry dates, and categorize food items based on processing levels.

3.Financial Assessment: Track expenses, estimate yearly losses, and predict future budgets using integrated financial data.

4.Analytical: Generate statistical insights, predict future trends, and assess the carbon footprint of food waste.


### Project Structure:

Entity Relationship Diagrams (ERDs): Detailed ERDs for each module, showing the relationships between different entities such as Food, Stalls, Waste, Inventory, and Financial data.

Normalization: Tables normalized up to 3NF, with some tables in 2NF due to their read-heavy nature, optimized for performance and data retrieval.

Triggers and Sequences: Implemented to automate updates between tables and ensure data integrity


License:
This project is open-source and free to use. You can modify and distribute the code as needed.

Authors: Santtosh Muniyandy
