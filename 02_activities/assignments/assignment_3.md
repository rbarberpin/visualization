# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    > Who is your intended audience? 
    
    > What information or message are you trying to convey with your visualization? 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    > What ‘underwater labour’ contributed to your final data visualization product?


    Visualization 1: Top 4 TPL Branches by Annual Circulation
   ![alt text](image-1.png)
C:\Users\Rachelb\visualization\02_activities\assignments\Visualization 1.ipynb
 
    > What software did you use to create your data visualization?
    I used Python with the following libraries: Pandas, Matplotlib, seaborn

    > Who is your intended audience? 
    Library administrators and planners interested in usage trends across branches,

    Policy makers focused on digital transformation,

    And researchers or community stakeholders interested in how library use is shifting over time.


    > What information or message are you trying to convey with your visualization? 
    
    The visualization aims to show how circulation volumes have evolved at the top 4 Toronto Public Library branches from 2012 to 2023, especially emphasizing the rise of the Virtual Library compared to physical branches like Agincourt, Fairview, and North York Central Library.


    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    Design choices focused on clarity, trend visibility, and comparison:

    I used distinct colors for each library branch to separate the lines.

    I added a title, axis labels, and a legend to guide interpretation.

    The y-axis was formatted in millions to match the scale of circulation.

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    I wrote a Python script that includes:Data loading, Cleaning Filtering (top 4 branches), and plotting. Because Python is code-based and version-controllable (e.g., using Jupyter Notebook or a .py script), anyone can rerun the script with the dataset to reproduce the chart. 

    > How did you ensure that your data visualization is accessible?  
    I considered accessibility by:

    Using color palettes that are distinguishable for colorblind users (avoiding red/green-only contrasts).

    Labeling axes clearly.

    Using text instead of relying solely on color (e.g., a legend for each line).

    Maintaining sufficient contrast between plot elements and background.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Library staff, who can see how their branch compares over time and ommunity members interested in digital vs physical access to library materials.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I chose to include only: four library branches with the highest total circulation, to avoid overcrowding and highlight key trends and circulation volume and year, as they are directly tied to usage patterns.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    idden labor included: exploring and cleaning the dataset, which involved checking for nulls, ensuring consistent branch names, and formatting years, writing code to group and sum circulation by branch and year, deciding how to define the “top 4” branches (e.g., total over all years).

   Visualization 2: Top 10 Ministries that completed FOI requests in 2020
   C:\Users\Rachelb\visualization\02_activities\Visualization2.csv
   What software did you use to create your data visualization?
   I used Microsoft Excel to create my data visualization. Excel was chosen because I had access to it and wanted to build my skills using pivot tables and charts. 
    > Who is your intended audience?
    The intended audience includes policy analysts, journalists, and members of the public interested in government transparency and access to information practices. It may also be relevant to ministry staff or researchers studying public service performance. 
    
    > What information or message are you trying to convey with your visualization? 
    I aimed to highlight which ministries received and completed the most FOI (Freedom of Information) requests in 2020, focusing attention on the volume and distribution of requests across ministries. This can help surface which parts of government are most frequently asked for information.


    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I focused on clarity, simplicity, and ranking. To improve readability:

    I selected only the top 10 ministries to avoid overcrowding the chart.

    I sorted the bars from largest to smallest to visually reinforce comparisons.

    I adjusted the bar width (gap width) for better visual impact.

    I added a clear title and axis labels to guide interpretation.

    I added data labels to the each bar so that anyone looking at the graph would be able to quickly see the total amount each bar had. 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    I used filters and PivotTables to isolate data for 2020.
    
    I saved the original dataset and a cleaned version, and noted any transformations.


    > How did you ensure that your data visualization is accessible? 

    I chose high-contrast colors for the bars.
    
    I used text labels and titles instead of relying on hover features or tooltips.
    
    I kept the chart structure simple, without clutter or unnecessary graphics.

    > Who are the individuals and communities who might be impacted by your visualization?  
    
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
     I chose to focus only on: Ministry, Year, and Requests Completed. This was done to maintain clarity and directly address the question of which ministries processed the most FOI requests in 2020.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Cleaning and filtering the dataset, especially selecting only 2020 data and removing unneeded rows.

    Sorting and verifying accuracy of the top 10 ministries.

    Formatting and styling the chart for clarity (adjusting labels, axis scales, bar width, title).

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.

