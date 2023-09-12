**Project Title:** Pharmacy Management System

**Project Description:**

The Pharmacy Management System is a comprehensive software application designed to streamline and enhance the operations of a pharmacy. It leverages the principles of Object-Oriented Programming (OOP) and several design patterns to ensure efficient management of medicines, inventory, orders, billing, and invoicing.

**Key Features:**

1. **Login Form:**
   - Implement the State Pattern to control user access based on working hours.
   - Authenticate users with secure login credentials.

2. **Add/Remove Medicine Form:**
   - Apply the Factory Method Pattern using `MedicineFactory` to add new medicines (e.g., Vitamins, Painkillers, Antibiotics).
   - Allow authorized personnel to remove medicines from the inventory.

3. **Update Stock Form:**
   - Enable authorized users to update medicine stock quantities.

4. **Check Stock Form:**
   - Display a list of available medicines and their current stock levels.
   - Implement the Adapter Pattern to ensure compatibility between data types in the database and the application.

5. **Add Order Form:**
   - Allow pharmacy staff to place orders for medicines when stock levels are low.
   - Utilize the Strategy Pattern for calculating order totals and applying discounts for different payment methods (cash or card).

6. **Billing Form:**
   - Generate bills for customers based on the medicines purchased.
   - Calculate the total amount to be paid and apply any applicable discounts.

7. **Generate Invoice Form:**
   - Create detailed invoices for completed transactions.
   - Include customer information, purchased medicines, quantities, prices, and total amount.
   - Save invoices in the SQL database for future reference.

**Design Patterns and OOP Concepts:**

- **Factory Method Pattern:** Used to create different types of medicines in the `Add/Remove Medicine` module.

- **Singleton Pattern:** Ensures that there's only one instance of the `Inventory Manager`, preventing conflicts when adding or removing medicines.

- **Adapter Pattern:** Ensures compatibility between the data types used in the system and the SQL database.

- **Strategy Pattern:** Determines how discounts are applied and payment information is processed in the `Add Order` and `Billing` modules.

- **State Pattern:** Manages the application's state, locking access outside working hours in the `Login` module.

**Database Integration:**

- Utilize SQL as the database management system to store information about medicines, inventory, orders, customers, and invoices.

**Technologies:**

- C# for Windows Forms application development.
- SQL for database management.
- Visual Studio for development and debugging.

This Pharmacy Management System aims to provide a user-friendly and efficient solution for managing pharmacy operations while adhering to OOP principles and incorporating essential design patterns for robust software architecture.
