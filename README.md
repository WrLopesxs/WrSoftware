🧾 WrSoftware - Snack Bar POS System
A complete Point-of-Sale system designed for snack bars or small restaurants. Built in C# with Windows Forms and SQL Server. Developed by Wender (WrSoftware), this system simulates a real-world flow of ordering, kitchen communication, and product management.

🛠 Features
🔐 Secure login with user access levels (Administrator / Kitchen)

📝 New order registration with product, beverage, condiments

🧑‍🍳 Kitchen display: updates automatically from XML file

📦 Product and beverage stock management

🧾 PDF summary generation of orders

💾 Orders saved as XML for record keeping

🧹 Order cancellation with reason and timestamp

📊 Ready for counter attendant workflow

💻 Technologies
C# with Windows Forms (.NET Framework)

SQL Server LocalDB

XML (for kitchen sync and order logs)

iTextSharp (for PDF generation)

🧪 Requirements
Visual Studio 2022 or later

SQL Server LocalDB or SQL Server Express

.NET Framework (v4.7.2 or higher)

🚀 Getting Started
Clone the repository

bash
Copiar
Editar
git clone https://github.com/your-username/WrSoftware.git
Open the solution (.sln) in Visual Studio

Run the SQL script in /database/estrutura.sql using SQL Server Management Studio to create the database.

Make sure your connection string matches this:

csharp
Copiar
Editar
"Data Source=(localdb)\\MSSQLLocalDB;Initial Catalog=Lanchonete;Integrated Security=True"
Run the project!
Login credentials:

Username: admin

Password: 123

for the kitchen
Username: Cozinha

Password: 123

📂 Folder Structure
/src → All C# code (Forms, logic, etc.)

/database → SQL script to create the database


👨‍💻 Developer
Made with care and attention to detail by Wender (WrSoftware).
This project was created as a school assignment and evolved into a fully functional POS solution.

