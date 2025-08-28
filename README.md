# Introduction

These two dashboards were designed for job seekers to address a common challenge: job market information is often scattered and difficult to interpret. By leveraging a real-world 2024 dataset of data 
job postings (covering titles, salaries, and locations), the project delivers a clear and accessible way to explore industry trends and compensation patterns.

# Background

The tech job market is one of the fastest-changing industries, and understanding it can be overwhelming for job seekers. Salaries, skills, and hiring trends vary not only by role but also by region and time. By working with real-world datasets of 2024 job postings (spanning data and IT roles), this project set out to explore the structure of the job market and provide clarity through interactive dashboards.

The **dashboards** were guided by a few key questions:

- Which roles are in highest demand, and how do their salaries compare?

- What are the most in-demand technical skills across job postings?

- How do job opportunities differ by region and work type (remote vs on-site)?

- What trends can be seen over time in job postings and salaries?

- How many skills, on average, do employers expect from IT and data professionals?

Answering these questions through **Power BI dashboards** not only uncovered valuable job market insights but also served as a practical way to sharpen my skills in data transformation, modeling, and visualization.

# Tools I Used

This projects were a hands-on journey with **Power BI**, applying a wide range of features to turn raw data into interactive **insights**:

- **Power Query (ETL)**: Cleaned, transformed, and shaped the dataset by handling blanks, changing data types, and creating new columns.

- **Data Modeling**: Built efficient models with relationships, applying Star Schema principles for better performance and scalability.

- **DAX Calculations**: Created custom measures and aggregations (e.g., Median Salary, Job Count, KPIs) to extract key insights.

 **Visualizations**:

- **Core charts** (Column, Bar, Line, Area) to compare trends and distributions.

- **Map charts** for geospatial analysis of job locations.

- **Cards & KPI** indicators to highlight critical metrics.

- **Tables** for detailed, sortable data views.

- A mix of common and uncommon **chart** types for effective storytelling.

- **Dashboard Design**: Focused on creating a clear, intuitive, and visually engaging layout.

 **Interactivity**:

- **Slicers** for dynamic filtering.

- **Buttons & Bookmarks** for smooth navigation and customized report views.

- **Drill-Through** designed as a button labeled “Find out Job Details”, allowing users to move from a high-level summary directly into detailed job insights.

# Project: Data Jobs Dashboard

This **Power BI** project analyzes the 2024 data job market using a real-world dataset of job postings. I designed two interactive **dashboards**:

1. **Overview Dashboard** – Highlights key KPIs like median salaries, job count, top-paying roles, and job posting trends.

2. **Drill-Through Dashboard** – Activated via the “Find Out Job Details” button, providing job-specific insights such as location, work-from-home availability, degree requirements, and benefits.

The project showcases my skills in **Power Query (ETL), data modeling, DAX measures, and dashboard design**, combining analytics with clear storytelling.

![1_pr_demonstration.gif](pictures/1_pr_demonstration.gif)

*Check it out here:* [1_project.pbix](1_project.pbix)

**Key Insights:**

- **Top-Paying Roles**: Senior Data Scientists and Machine Learning Engineers lead with median salaries above $150K.

- **Market Trends**: Job postings peaked early in 2024 (~55K in February) but declined steadily to ~14K by November.

- **Job Distribution**: Most opportunities are concentrated in North America and Europe, with full-time positions making up 91% of listings.

# Project: IT Jobs Dashboard
This **dashboard** visualizes the IT job market using a dataset of nearly half a million job postings. It provides insights into salaries, job demand, and required skills. The interactive filters (job title, country, and slicer reset) make it easy for job seekers to explore opportunities and market trends.

![2_pr_demonstration.gif](pictures/2_pr_demonstration.gif)

*Check it out here:* [2_project.pbix](2_project.pbix)

**Key Insights:**

- **High Salaries in Data Roles** – Senior Data Scientist and Machine Learning Engineer are among the top-paying jobs, with median salaries above $150K.

- **Python & SQL** Dominate – These two skills are by far the most in-demand, appearing in nearly half of all postings.

- **Skill Intensity** – On average, jobs require about 5 different skills, showing the growing need for multidisciplinary expertise in IT.

# What I Learned

Through building these **Dashboards**, I strengthened both my **Power BI** development and data transformation skills. Key takeaways include:

- **DAX**: Creating new measures using functions like `COUNT()`, `CALCULATE()`, `ALLSELECTED()`, `MEDIAN()` and etc. to calculate salaries, job counts, and averages dynamically.

- **Power Query**: Performing data cleaning and transformation (`Trim()`, replacing values, reordering columns, changing data types, creating additional columns) and **merging/appending** queries.

- **M Language**: Correcting minor issues and optimizing transformations directly in the query editor. `= Table.RenameColumns(#"Reordered Columns",{{"Custom", "skills"}})` *(renamed columns)*

- **Visual Design**: Choosing the right **charts**, configuring their properties, and presenting detailed data with **Matrix** visualizations.

- **Interactivity**: Adding **slicers and parameters** for filtering, **drill-through** functionality for job-level details, and navigation with **buttons and cards**.

- **Dashboard Storytelling**: Combining job market data into clear KPIs (salary, job count, skills required) and insights to make the dashboard both analytical and user-friendly.

# Special Thanks

I would like to extend my sincere thanks to **Luke Barousse** for offering a comprehensive Data Analyst course and sharing a rich dataset with his subscribers, including myself. His content was instrumental in building my understanding of **Power BI**'s role in **Data Analysis** and served as the foundation for **this project**. I also want to acknowledge **ChatGPT**, which provided valuable support and guidance throughout the development of this project.

*Luke Barousse Reference:* [Luke Barousse YT](https://www.youtube.com/@LukeBarousse)

# Conclusion

This project demonstrates how raw job posting data can be transformed into meaningful insights through **Power BI**. By combining data cleaning, modeling, and interactive dashboard design, I built tools that not only highlight key trends in the 2024 job market but also make them accessible for job seekers and professionals.

Through this process, I improved my skills in **DAX, Power Query, data visualization**, and storytelling with data. More importantly, I learned how to ask the right analytical questions and translate them into clear answers through visuals.

These dashboards are a practical example of how analytics can support decision-making — whether for individuals planning their careers or organizations tracking labor market trends.

