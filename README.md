# School District Performance Analysis
**Overview**

This project simulates district-wide standaridzed test performance through a simulated education analytics scenario. Acting in the role of a data aalyst for a city district, the object is to evaluate student match and reading outcomes, identify performance trends, and generate insights that could inform strategic planning and resource allocations.

Using **Pandas** and **Jupyter Notebook**, this analysis aggregated student- and school-level data to produce district sumamries, school comparisons, and performanc breakdowns across multiple dimensions.

## Dataset
The Dataset incldues the following:
* Student-level math scores
* Student-level reading scores
* Grade level information (9th-12th)
* School-level information (e.g., school name, type, size, budget, etc.)

## Analysis Breakdown
### **District Summary**
A high-level snapshot of distric perfomance, including: 
* Total number of schools
* Total number of students
* Total district budget
* Average math score
* Average reading school
* Percentage passing math
* Percentage passing reading
* OVerall passing rate (Students passing both subjects)

### **School Summary**
A school-by-school peformance breakdown including:
* School name
* School type
* Total students
* Total school budget
* Per-Student budget
* Average match score
* Average reading score
* Percentage passing math
* Percentage passing reading
* Percentage overall passing

### **Performance Rankings**
**Top Performaing Schools**

Schools ranked by highest overall passing percentage.

**Lowest Performaing Schools**

Schools ranked by lowest overall passing percentage.

### **Academic PErformance by Grade Level**
* Average math score by grade (9th-12th) for each school
* Average reading scores by grade (9th-12th) for each school

### **Performance by Spending**
Schools are grouped into spending ranges based on per-student budget:
* <$585
* $585-630
* $630-645
* $645-680

For each spending range, the analysis includes:
* Average math score
* Average reading score
* Percentage passing math
* Percentage passing reading
* Percentage overall passing

### **Performance by School Size**
Schools are categorized into:
* Small (<1000 students)
* Medium (1000-2000 students)
* Large (2000-5000 studnets)

For each size category, the following metrics are calculated:
* Average math score
* Average reading score
* Percentage passing math
* Percentage passing reading
* Percentage overall passing

### **Performance by School Type**
A comparison of academic performance based on school type (e.g., Charter vs District), inclding
* Average math score
* Average reading score
* Percentage passing math
* Percentage passing reading
* Percentage overall passing

### **Key Insights**
The final report includes written observations highlighting at least two major trends identified in the data. These inisghts focus on relationships between
* School funding and academic performance
* School size and student outcomes
* School types and passing rates
