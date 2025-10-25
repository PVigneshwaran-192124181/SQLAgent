#  AI SQL Agent — Natural Language to SQL Converter

### Overview
A Java + MySQL + OpenAI-based project that converts English questions into SQL queries and executes them automatically.

### Example
**Input:** Show all employees with salary between 10000 and 20000
**Output SQL:** SELECT * FROM employees WHERE salary BETWEEN 10000 AND 20000;
**Result:**
| emp_id | emp_name     | department | salary | city       |
| ------ | ------------ | ---------- | ------ | ---------- |
| 101    | Rajesh Kumar | HR         | 12000  | Chennai    |
| 104    | Priya Nair   | IT         | 18000  | Bengaluru  |
| 107    | Manoj Reddy  | Sales      | 15000  | Hyderabad  |
| 110    | Kavitha Devi | Finance    | 19000  | Coimbatore |

### Tech Stack
- Java 17
- JDBC + MySQL
- OpenAI API
- Maven

### How to Run
1. Clone the repo  
2. Import in Eclipse as Maven project  
3. Set OpenAI API key  
4. Run `AISQLAgent.java`

### Screenshots
1. (  "C:\Users\Vigneshwaran\OneDrive\Desktop\SqlAgent\Screenshot\fetch name - 1 input.png" )
   (  "C:\Users\Vigneshwaran\OneDrive\Desktop\SqlAgent\Screenshot\fetch name - 2 Input,Output.png"  )
2. ("C:\Users\Vigneshwaran\OneDrive\Desktop\SqlAgent\Screenshot\Fetching employees salary NLP to SQL Query.png" )  
- Console running output  
- MySQL table view in Workbench

### Author
**Vigneswaran P** — Final Year (AI&DS) Student 
GitHub: [ https://github.com/PVigneshwaran-192124181 ]
