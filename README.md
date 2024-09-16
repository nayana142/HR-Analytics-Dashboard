# HR-Analytics-Dashboard
HR Analytics Dashboard: Employee Attrition, Performance, and Satisfaction Insights
![Screenshot 2024-09-16 163513](https://github.com/user-attachments/assets/4376ce0c-408c-4343-942b-9715adfe50a0)
![Screenshot 2024-09-16 163537](https://github.com/user-attachments/assets/75fc9ce1-ab6c-44cf-a79f-b45494bb6d51)

## Overview
This Power BI dashboard provides insights into employee performance, attrition, and satisfaction based on HR analytics data. It allows HR managers and stakeholders to analyze various aspects such as employee job satisfaction, work-life balance, training opportunities, and attrition trends. This data-driven approach can help identify factors influencing employee retention and performance, allowing for informed decision-making.

## Datasets
The dashboard is based on the following key datasets:

## 1. Fact PerformanceRating
    PerformanceID: Unique identifier for each performance review.
    EmployeeID: Unique identifier for the employee being reviewed.
    ReviewDate: Date of the performance review.
    EnvironmentSatisfaction: Rating of the employee's satisfaction with their work environment.
    JobSatisfaction: Rating of the employee's job satisfaction.
    RelationshipSatisfaction: Rating of the employee's satisfaction with workplace relationships.
    TrainingOpportunitiesWithinYear: Number of training opportunities available in the year.
    TrainingOpportunitiesTaken: Number of training opportunities the employee has taken.
    WorkLifeBalance: Rating of work-life balance.
    SelfRating: Employee’s self-assessment of performance.
    ManagerRating: Manager’s performance rating of the employee.
## 2. DimEmployee
    EmployeeID: Unique identifier for each employee.
    FirstName: Employee’s first name.
    LastName: Employee’s last name.
    Gender: Employee’s gender.
    Age: Employee’s age.
    BusinessTravel: Frequency of business travel.
    Department: Department where the employee works.
    DistanceFromHome (KM): Distance between the employee's home and the workplace.
    State: State where the employee resides.
    Ethnicity: Employee's ethnicity.
    MaritalStatus: Employee’s marital status.
    Salary: Annual salary of the employee.
    StockOptionLevel: Stock options level granted to the employee.
    OverTime: Indicates whether the employee works overtime (Yes/No).
    HireDate: Date of employment.
    Attrition: Indicates whether the employee has left the company (Yes/No).
    YearsAtCompany: Number of years with the company.
    YearsInMostRecentRole: Number of years in the most recent role.
    YearsSinceLastPromotion: Number of years since the last promotion.
    YearsWithCurrManager: Years spent working with the current manager.
## 3. SatisfiedLevel
    SatisfactionID: Unique identifier for satisfaction level.
    SatisfactionLevel: Employee's satisfaction level ranging from "Very Dissatisfied" to "Very Satisfied."
## 4. RatingLevel
    RatingID: Unique identifier for performance rating.
    RatingLevel: Performance rating, from "Unacceptable" to "Above and Beyond."
## 5. EducationLevel
    EducationLevelID: Unique identifier for education level.
    EducationLevel: Level of education achieved by the employee, ranging from "No Formal Qualifications" to "Doctorate."
## Key Insights
    Attrition Analysis: Examine which factors (e.g., salary, distance from home, satisfaction levels) are influencing employee attrition.
    Performance Review: Visualize employee performance ratings from both self-assessment and manager evaluations.
    Satisfaction Levels: Track work-life balance, job satisfaction, and environmental satisfaction ratings across different departments and employee demographics.
    Training Opportunities: Analyze the relationship between training opportunities provided and taken by employees and how they impact overall satisfaction and performance.
    Employee Demographics: Understand the impact of factors such as gender, age, business travel, and education levels on employee attrition and performance.
## Usage
    Open Power BI: Open the Power BI file containing the dashboard.
    Connect to Data: Load the datasets to visualize employee attrition and performance trends.
    Explore Dashboard: Use the provided filters to drill down into specific departments, employee groups, or satisfaction levels for detailed insights.
Interpret Results: Gain actionable insights to improve employee retention, optimize performance reviews, and address factors contributing to job satisfaction.
Conclusion
This dashboard provides a comprehensive view of HR analytics, focusing on employee attrition, performance, and satisfaction. By leveraging the insights from this dashboard, organizations can make strategic decisions to enhance employee satisfaction, retention, and overall company performance.
