# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      
"For my example of a poor visualization, I selected the Tableau visualization *Formula 1 Constructors (2006–2025)*. The chart uses a radial bump chart to display Formula 1 constructor rankings over time, with each team represented by a different colored line. At first glance, the visualization is visually appealing because of its circular layout, dark background, and vibrant colors. However, its design makes the information more difficult to interpret than necessary.
A first issue is the radial layout. Time-based data is usually easier to understand when presented in a linear, left-to-right format because viewers can naturally follow changes over time. In this chart, the years are arranged around a circle, forcing viewers to trace curved lines and move their attention around the entire visualization. It is also not immediately clear whether positions closer to the center represent better or worse rankings.
Secondly, the chart’s purpose is unclear. The title does not communicate what viewers are supposed to learn from the visualization. Effective visualizations should be designed around a specific user task. As Munzner (2009) argues, visualization design should begin with an understanding of the user’s goals and data before selecting a visual form. In this case, the chart includes several dimensions—time, rankings, and teams—but does not make any one task easy to accomplish.
The chart also suffers from visual clutter. Viewers must repeatedly consult the legend, match colors to teams, and follow lines around the circle without losing track of them. While dedicated Formula 1 fans may find the chart manageable, it is less accessible to a general audience. Research by Goldberg and Helfman (2011) found that radial graphs often take longer to interpret than linear graphs, while Waldner et al. (2020) reported that linear layouts generally produce greater accuracy and efficiency."

    - How could this data visualization have been improved?  
      ```
"This visualization could be improved by replacing the radial bump chart with a standard linear bump chart or line chart. A left-to-right timeline would make it easier for viewers to follow changes in constructor rankings across seasons and compare teams over time. The chart should also include a more descriptive title that clearly communicates its purpose, such as highlighting ranking changes or identifying dominant constructors over the last 20 seasons. To reduce visual clutter, the number of displayed teams could be limited to the most successful constructors, or interactive filtering could allow users to select specific teams of interest. Direct labels placed at the ends of lines could also reduce reliance on a separate legend. Finally, clearer axis labels and annotations highlighting major ranking changes or championship-winning seasons would help viewers quickly identify important trends and insights. These changes would improve readability, reduce cognitive effort, and make the visualization more effective for both Formula 1 fans and general audiences."

Good Data Visualization

"For my example of an effective visualization, I selected *Health Tracker* by Tobiloba Babajide from Tableau Public's Healthcare collection. I chose this dashboard because it demonstrates principles of data visualization that are highly relevant to healthcare research and clinical decision-making. As a graduate student studying orthopaedic surgery, I frequently work with patient outcomes, recovery metrics, and longitudinal health data. Effective visualization is essential for identifying trends, monitoring progress, and communicating findings clearly to both clinicians and patients.
One of the dashboard's greatest strengths is its clear purpose. The visualization is designed to help users monitor health-related measures over time, allowing viewers to quickly identify patterns and changes in key metrics. The layout presents information in a structured manner, making it easy to understand what is being measured and why it is important. This aligns with Munzner's (2009) principle that visualizations should be designed around the user's task and the questions they are trying to answer.
The dashboard also makes effective use of time-series visualizations. Trends are displayed using familiar linear charts, which allow viewers to follow changes over time without unnecessary complexity. This is particularly valuable in healthcare settings where clinicians often need to track patient outcomes, rehabilitation progress, or postoperative recovery. For example, an orthopaedic surgeon could use a similar design to monitor pain scores, range of motion, functional outcome measures, or recovery milestones following joint replacement surgery. Because the data are displayed on a common scale, viewers can easily compare values across different time periods.
The visualization also minimizes visual clutter. The use of consistent colors, clear labels, and an organized layout reduces cognitive effort and allows viewers to focus on the data rather than the design itself. Cleveland and McGill (1984) found that position along a common scale is one of the most effective ways to communicate quantitative information, and this dashboard applies that principle effectively through its straightforward chart design.
Overall, *Health Tracker* is an effective visualization because it presents complex health information in a clear, accessible, and actionable format. Its emphasis on trends, organization, and usability makes it particularly relevant to healthcare professionals and researchers. For orthopaedic surgery, a similar dashboard could be used to monitor patient recovery, compare treatment outcomes, and support evidence-based clinical decision-making."

  - How could this data visualization have been improved?
" Although *Health Tracker* is an effective visualization, there are several ways it could be improved. First, the dashboard could provide additional contextual information, such as benchmark values, target ranges, or clinical thresholds. In healthcare settings, trends are often more meaningful when viewers can compare them against established standards. For example, an orthopaedic surgeon monitoring postoperative recovery would benefit from seeing whether a patient's progress falls within expected recovery ranges. Second, the dashboard could incorporate interactive filtering options that allow users to examine specific patient groups, conditions, or time periods. This would make the visualization more useful for detailed analysis and research. The dashboard could also benefit from annotations that highlight significant changes or unusual patterns in the data, helping users identify important events without having to search for them manually. Finally, providing additional information through tooltips or drill-down features could give users access to more detailed data while maintaining the dashboard's clean and uncluttered design. These enhancements would improve the dashboard's analytical value while preserving its strengths in clarity, organization, and usability."


- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
