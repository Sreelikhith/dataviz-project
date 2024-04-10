# Data Visualization Project

## Data

The data I propose to visualize for my project comprises detailed information on jobs in the data field. This dataset includes various attributes such as job titles, categories, salary information in both local currency and USD, employee residence, company location, experience level, employment type, work setting, and company size. The dataset spans multiple years and covers a wide range of positions within the data science and analytics industry worldwide.


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How does the average salary vary across different job categories and experience levels?
 * Is there a correlation between company size and salary ranges for data field positions?
 * Are there interesting geographical patterns in where data jobs are located versus where employees reside?
 * How does the distribution of employment types (full-time, part-time, contract) and work settings (remote, in-person, hybrid) vary across different regions and job categories?

## Self Critique of Initial Questions/Tasks

The project is designed to address the outlined tasks and questions effectively.

1. How Does the Average Salary Vary Across Different Job Categories and Experience Levels?
   
   Our visualization incorporates filters for job categories and experience levels. By allowing users to select specific categories and 
   experience levels, the visualization dynamically updates to display the average salary associated with the selected criteria.

   The dynamic update is likely achieved through the updateChart function, which filters the data based on user selections and recalculates the 
   average salary for the remaining dataset. The visualization then redraws the chart, specifically showing average salaries by job titles 
   within the chosen categories and experience levels. This approach enables users to explore salary variations across different job categories 
   and experience levels in an interactive manner.

2. Correlation Between Company Size and Salary Ranges?

   We have implemented a filter for company size, allowing users to explore how salary ranges vary across small, medium, and large companies. 
   This direct comparison can visually indicate if larger companies tend to offer higher salaries than smaller ones, thereby suggesting a 
   correlation between company size and salary range.

3. Geographical Patterns in Job Locations Versus Employee Residences?

   The filters for "Employee Residence" enable users to investigate geographical patterns. This mechanism allows for the exploration of where 
   jobs are located in relation to where employees live. By filtering the dataset for specific locations and comparing the distribution of job 
   locations with employee residences, users can identify trends, such as whether certain regions have a higher concentration of remote jobs or 
   if certain job categories are more prevalent in specific geographical areas.

4. Distribution of Employment Types and Work Settings Across Regions and Job Categories?

   This visualization includes filters for employment types (full-time, part-time, contract) and work settings (remote, in-person, hybrid). This 
   setup enables users to examine how these aspects vary across different regions and job categories. Selecting specific employment types or 
   work settings updates the visualization to reflect the distribution of these criteria within the chosen regions or job categories.

Aesthetics and Usability

The visualization maintains a clean and accessible design, with a consistent color scheme and clear labeling. However, ensuring high contrast for readability and potentially simplifying complex sections could enhance aesthetics. The interface is intuitive, with interactive filters that allow easy exploration of the dataset. Tooltips enhance the usability by providing immediate context. Still, adding a brief tutorial or guide could help new users navigate the visualization more effectively.

## Sketches

![IMG_0421](https://github.com/Sreelikhith/dataviz-project/assets/128874576/4fd291b4-11fa-4837-9322-b7225044ce76)

![IMG_0422](https://github.com/Sreelikhith/dataviz-project/assets/128874576/84492609-894c-46f6-9e1e-c7cd0259bbb4)

The project will feature an array of interactive visualizations, including multiple bar charts equipped with dynamic filters and selection buttons, enabling users to navigate the data with ease and precision. For example, one visualization could offer a comparative view of average salaries across job categories, with the functionality to toggle between different experience levels at the click of a button. Another might display the distribution of jobs by employment type, allowing for deeper exploration into specific regions or job categories. To further enhance user experience and coherence across these interactive elements, a unified filter panel will be introduced. This panel will allow users to refine their view across various metrics—such as job category, experience level, and region—through a singular, streamlined action. This design approach not only enriches the navigation experience but also ensures that users can easily access and interact with the data according to their specific interests and inquiries, making the complex data landscape both accessible and engaging.


## Prototypes

I’ve created a proof of concept visualization of this data.


<img width="968" alt="Screenshot 2024-03-14 at 1 39 48 AM" src="https://github.com/Sreelikhith/dataviz-project/assets/128874576/3a1a3d58-bed7-46f7-8614-60e76baf331a">
(https://vizhub.com/Sreelikhith/bd6af7bd54f0461a8b6e45d474483ace)


## Open Questions

While I am confident in the project's direction, I'm still exploring the best approaches to implement button functionality effectively in the visualizations and making the visualization responsive and intuitive for users with varying levels of familiarity with data analysis.

## Milestones

* Week 9: Finalize dataset preparation and initial data analysis.
* Week 10: Develop the prototype with basic interactivity and visualizations focusing on salary insights.
* Week 11-12: Expand the prototype to include other visualizations and employment type distributions.
* Week 13-14: Refine interactivity features, such as filters and toggles, to enhance user engagement and exploration.
* Week 15: Gather feedback and identify areas for improvement.
* Week 16: Implement feedback, improve the visualizations and usability, and prepare the final presentation.
