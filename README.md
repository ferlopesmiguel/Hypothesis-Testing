The analyzed dataset is a sample of data-related jobs and salaries, containing the following information:

work_year: Indicates the year the data was recorded, providing a temporal context crucial for understanding salary trends over time.

job_title: Specifies the specific job role, such as 'Data Scientist', 'Data Engineer', or 'Data Analyst', facilitating an analysis of salary distribution across various specialized roles within the data field.

job_category: Classifies the job role into broader categories like 'Data Analysis', 'Machine Learning', and 'Data Engineering', enabling more accessible analysis and categorization.

salary_currency: Represents the currency the salary is paid (e.g., USD, EUR), essential for currency conversion and contextualizing the salary globally.

Salary: Provides the annual gross salary of the role in the local currency, serving as a critical figure for direct regional salary comparisons.

salary_in_usd: Presents the annual gross salary converted to United States Dollars (USD), aiding global salary comparisons and analyses with a uniform currency.

employee_residence: Specifies the team member's country of residence, offering insights into geographical salary differences and cost-of-living variations.

experience_level: Classifies the professional experience level into categories like 'Entry-level', 'Mid-level', 'Senior', and 'Executive', offering insights into how experience influences salary in data-related roles.

employment_type: Specifies the type of employment, such as 'Full-time', 'Part-time', and 'Contract', facilitating an analysis of how different employment arrangements affect salary structures.

work_setting: Describes the work setting or environment, like 'Remote', 'In-person', or 'Hybrid', reflecting the impact of work settings on salary levels in the data industry.

company_location: Indicates the country where the company is located, aiding in the analysis of how the company's location affects salary structures.

company_size: Represents the size of the employer company, often categorized into small (S), medium (M), and large (L) sizes, allowing for an analysis of how company size influences salary.

After carrying out the EDA, I decided to only analyze management positions to ensure the same criteria and avoid skews in the analysis.
The null hypothesis is that in-person jobs have higher salaries than remote jobs. After analyzing the distribution of salaries, I observed that it does not follow a normal distribution.
Then I used the Wilcoxon-Mann-Whitney method for each job category available in the sample to test the null hypothesis.
You can check the estimated result for the population at the end of the code stored in the variable df_results.
