# sql-challenge

Background
    It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the      1980s and 1990s. All that remains of the employee database from that period are six CSV files.


Note: For this project, the tables are designed to hold the data from the CSV files, have the CSV files imported into a SQL database(PgAdmin4), and then answer questions about the data. These activities cover data modelling,    data engineering, and data analysis, respectively.


Data Modelling (represented by ERD)
    Inspect the CSV files, and then sketch an ERD of the tables. To create the sketch, feel free to use a tool like QuickDBDLinks to an external site. please see attached ERD.png 

Data Engineering (covered in Data_Engineering_EmployeeSQL_db.sql)
    Use the provided information to create a table schema for each of the six CSV files. Be sure to do the following:
      Remember to specify the data types, primary keys, foreign keys, and other constraints.
      For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.
      Be sure to create the tables in the correct order to handle the foreign keys.
      Import each CSV file into its corresponding SQL table.

Data Analysis (covered in Data_Analysis_questions.sql)
    List the employee number, last name, first name, sex, and salary of each employee.
    List the first name, last name, and hire date for the employees who were hired in 1986.
    List the manager of each department along with their department number, department name, employee number, last name, and first name.
    List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
    List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
    List each employee in the Sales department, including their employee number, last name, and first name.
    List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
    List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).


