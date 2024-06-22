# User Experience Analysis of Nested Menu Designs

## Project Overview

This project involves a comprehensive user experience study comparing three types of nested menus (Nested Fisheye, Nested Dropdown, Accordion) in goal-oriented web navigation tasks. The study aimed to evaluate the efficiency, user satisfaction, ease of use, and ease of learning for each menu type. 

## Project Details

### Design and Implementation
- **Technologies Used**: HTML, CSS
- **Description**: Designed and implemented three nested menu types to facilitate the user experience study.

### End-User Testing
- **Testing Process**: Conducted structured end-user testing that included pre-test questionnaires to gather demographic data, task-based evaluations to measure task completion times, and post-task Likert scale feedback to assess user satisfaction and ease of use.

### Data Analysis
- **Tools Used**: Python, pandas, scipy
- **Statistical Analysis**: Analyzed user interactions and feedback using descriptive statistics, ANOVA, and post-hoc tests.
- **Visualization**: Created visual reports using matplotlib and seaborn to effectively present the study findings.

## Key Findings
- **Task Completion Times**: 
  - Nested Dropdown: 32.34 seconds (fastest)
  - Accordion: 37.73 seconds
  - Nested Fisheye: 41.13 seconds (slowest)
- **User Experience Ratings** (Likert scale of 1-5): 
  - **Providing a Frustrating/Satisfying Experience**:
    - Nested Dropdown: 4.208
    - Accordion: 3.75
    - Nested Fisheye: 3.375
  - **Ease of Use**:
    - Nested Dropdown: 4.167
    - Accordion: 3.708
    - Nested Fisheye: 2.917
  - **Ease of Learning**:
    - Nested Dropdown: 4.25
    - Accordion: 3.75
    - Nested Fisheye: 3.375
- **Ease of Learning and Technological Proficiency**:
  - The correlation between technological capability and ease of learning ratings, calculated for each menu type, showed the following:
    - Nested Fisheye: 0.8323
    - Nested Dropdown: 0.7242
    - Accordion: 0.6083
- **User Preferences and Performance**:
  - Descriptive statistics for task completion times and user feedback were calculated for each menu type.
  - **Completion Times**:
    - Nested Dropdown: Mean: 32.34 seconds, Std Dev: 11.57, Min: 15.08 seconds, Max: 58.08 seconds, Median: 29.65 seconds
    - Nested Fisheye: Mean: 41.13 seconds, Std Dev: 11.38, Min: 25.36 seconds, Max: 64.31 seconds, Median: 40.64 seconds
    - Accordion: Mean: 37.73 seconds, Std Dev: 11.84, Min: 22.22 seconds, Max: 59.18 seconds, Median: 36.82 seconds
  - **User Feedback**:
    - Nested Dropdown: Mean: 4.17, Std Dev: 1.01, Min: 2.00, Max: 5.00, Median: 5.00
    - Nested Fisheye: Mean: 2.92, Std Dev: 0.93, Min: 1.00, Max: 5.00, Median: 3.00
    - Accordion: Mean: 3.71, Std Dev: 0.86, Min: 2.00, Max: 5.00, Median: 4.00

**Summary**: The Nested Dropdown menu was found to be the most efficient and user-friendly, with the fastest task completion times and highest user satisfaction and ease of use ratings. The Accordion menu showed moderate performance and appealed to a broader user base, making it a viable option for various applications. However, the Nested Fisheye menu was less effective for goal-oriented tasks due to slower completion times and lower user satisfaction and ease of use ratings, making it more suitable for browse-oriented tasks where detailed exploration is necessary. Future research should include a more diverse participant group and consider live A/B testing for more accurate data, and additional parameters such as error rates could provide a more comprehensive perspective.

## Conclusion and Recommendations
- **Efficiency**: The Nested Dropdown menu was the most efficient and user-friendly for goal-oriented tasks.
- **User Appeal**: The Accordion menu showed moderate performance, appealing to a wider user base.
- **Suitability**: The Nested Fisheye menu was less effective for goal-oriented tasks, more suited for browse-oriented tasks.

## How to Use This Repository
1. **Clone the Repository**: 
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. **Open the Jupyter Notebook**: 
    - Navigate to the notebook file and open it using Jupyter Notebook or Jupyter Lab.
3. **Explore the Data and Analysis**:
    - Follow the steps in the notebook to understand the data analysis process and results.

## Acknowledgments
This project was conducted as part of a user experience study in goal-oriented web navigation tasks, analyzing the effectiveness of various menu designs.
