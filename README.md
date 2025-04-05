# 🏭 Warehouse Management System (Java Swing)

This is a Java Swing-based desktop application that I developed to manage warehouse operations. This application was part of my early software development journey with **IZAR Tech**, a startup I co-founded.

> ⚠️ **Note:** This repository contains only the **build files**. The source code is not available, but the application itself is fully functional.

---

## 📦 Features

- **Warehouse Management**: Add, edit, and delete warehouse items.
- **Inventory Tracking**: Keep track of stock levels.
- **Reporting**: Generate various warehouse and inventory reports.
- **User Interface**: Built with Java Swing, offering a simple and efficient interface.

---

## 🛠️ Built With

- **Java SE**: For the core application logic.
- **Java Swing**: For the graphical user interface (GUI).
- **MySQL**: For database management.
- **JasperReports**: For generating and managing reports.
- **NetBeans IDE**: For project structure and build.

---

## 🚀 How to Run

1. **Clone or Download** this repository to your local machine.
2. **Import the MySQL Database**:
   - Go to bin Schema inventio.txt and copy the script inside the .txt file run it in mysql env.
   - Go to the `db` folder in this repository.
   - Import the SQL files into your MySQL server. The files include:
     - `inventio_branches.sql`
     - `inventio_cart.sql`
     - `inventio_drivers.sql`
     - `inventio_employee.sql`
     - `inventio_product.sql`
     - `inventio_sales.sql`
     - `inventio_stock_in.sql`
     - `inventio_storage.sql`
   - Ensure your MySQL server is running and accessible.
3. **Run the Application**:
   - open `inventio.jar`
   - the default (username and password): (admin, admin).

## 📁 Project Structure

```bash
Warehouse-Management-System/
├── bin/
│   ├── Schema inventio.txt        # Database schema information
│   └── icon.ico                   # Application icon
├── config.xml                     # Configuration file
├── db/                            # SQL files for the database
│   ├── inventio_branches.sql
│   ├── inventio_cart.sql
│   ├── inventio_drivers.sql
│   ├── inventio_employee.sql
│   ├── inventio_product.sql
│   ├── inventio_sales.sql
│   ├── inventio_stock_in.sql
│   └── inventio_storage.sql
├── inventio.jar                   # Main executable JAR file
├── launch4j.log                   # Log file for launch4j
├── lib/                           # Required JAR dependencies
│   ├── AbsoluteLayout.jar
│   ├── commons-beanutils-1.9.4.jar
│   ├── commons-collections-3.2.1-1.0.0.jar
│   ├── commons-digester-1.7.jar
│   ├── jasperreports-6.5.1.jar
│   ├── jasperreports-fonts-6.20.0.jar
│   ├── jasperreports-javaflow-6.20.0.jar
│   ├── jcalendar-1.4.jar
│   ├── jgoodies-common-1.2.0.jar
│   ├── jgoodies-looks-2.4.1.jar
│   ├── junit-4.6.jar
│   ├── mysql-connector-j-8.0.33.jar
│   ├── org-apache-commons-logging.jar
│   └── swingx-all-1.6.4.jar
├── reports/                       # Report templates (JasperReports)
│   ├── branchReport.jrxml
│   ├── product.jrxml
│   ├── salesReport.jrxml
│   ├── stockReport.jrxml
│   └── others...
└── README.md                      # This file
```

## 📚 Background

The Warehouse Management System (WMS) was developed to streamline inventory and stock management for small businesses. The project was a key milestone in my journey with IZAR Tech, and although the startup didn’t survive, the lessons learned continue to shape my approach to software development today.

## 🧠 Lessons Learned

- Database Integration: Working with MySQL and Java for data storage was crucial in building scalable and functional software.
- Swing UI: Java Swing, although outdated, remains a solid choice for building desktop applications.
- Project Management: This project taught me about deadlines, client expectations, and the importance of proper documentation.

## 📬 Feedback

I’d love to hear your thoughts on the project! If you’ve worked on something similar, or if you have suggestions for improvements, feel free to open an issue or message me on (LinkedIn)[https://www.linkedin.com/in/alialghanay/].

## 📜 License

This repository is shared for educational and historical purposes. Feel free to explore and learn from it!
