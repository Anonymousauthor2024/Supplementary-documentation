# Quantitative Analysis Results

The quantitative analysis of this study is divided into two steps: **descriptive statistics of categories** and the **significance analysis of differences between subcategories**.

In the phase of descriptive statistical analysis, we comprehensively calculated key metrics across different subcategories, including absolute values, proportions, and mean values. This analysis aims to provide a preliminary understanding of the community's engagement and attention levels towards various discussion topics. Through the examination of these fundamental data, we can **initially observe and interpret the behavioral characteristics of community members**.

Next, we employ Analysis of Variance (ANOVA) as the primary tool to **verify the statistical significance of the above-observed differences**. The ANOVA allows us to determine whether discussions on different subcategories lead to significant differences in user behavior characteristics. 
By establishing whether there are significant group differences among the variables **overall**, we further apply post hoc analysis (LSD test) to examine the **specific** manifestations and implications of these differences.

The following tables are related to our analysis.


### Descriptive Statistical Analysis of Community Engagement by Category
This table aggregates statistical measures across various subcategories, providing absolute values and percentages for posts, comments, and involved users. Additionally, it presents average values for comments, upvotes, downvotes, and upvote ratios. Each category is defined by distinct themes as referenced in Qualitative Study: GPT-4 Analysis.md, where a full description of each category can be found. These statistics objectively reflect the level of community interaction within each category, offering insights into how different topics garner varying degrees of engagement from the community.

| Category | Subcategory | post amount | post percentage | comments amount | comments percentage | involved users amount | involved users percentage | average comment | average upvote | average upvote ratio | average downvote |
|----------|-------------|-------------|-----------------|-----------------|---------------------|-----------------------|---------------------------|-----------------|----------------|---------------------|------------------|
| **1**    | **1.1**     | 147         | 16.2%           | 2076            | 8.9%                | 298                   | 9.1%                      | 14.1            | 42.5           | 78%                 | 3.8              |
|          | **1.2**     | 60          | 6.6%            | 2040            | 8.8%                | 126                   | 3.9%                      | 34.0            | 61.5           | 77%                 | 5.3              |
|          | **1.3**     | 34          | 3.8%            | 3533            | 15.2%               | 69                    | 2.1%                      | 103.9           | 255.2          | 78%                 | 26.7             |
|          | **1.4**     | 174         | 19.2%           | 3081            | 13.2%               | 388                   | 11.9%                     | 17.7            | 67.4           | 80%                 | 6.0              |
|          | **1.5**     | 23          | 2.5%            | 3917            | 16.8%               | 40                    | 1.2%                      | 170.3           | 633.4          | 77%                 | 49.8             |
|          | **1.6**     | 17          | 1.9%            | 473             | 2.0%                | 35                    | 1.1%                      | 27.8            | 53.5           | 77%                 | 4.0              |
| **2**    | **2.1**     | 139         | 15.4%           | 1005            | 4.3%                | 632                   | 19.4%                     | 7.2             | 21.0           | 77%                 | 2.3              |
|          | **2.2**     | 113         | 12.5%           | 1996            | 8.6%                | 373                   | 11.4%                     | 17.7            | 49.6           | 80%                 | 4.2              |
|          | **2.3**     | 68          | 7.5%            | 2425            | 10.4%               | 104                   | 3.2%                      | 35.7            | 36.5           | 75%                 | 4.8              |
| **3**    | **3.1**     | 61          | 6.7%            | 705             | 3.0%                | 498                   | 15.3%                     | 11.6            | 23.7           | 77%                 | 4.7              |
|          | **3.2**     | 69          | 7.6%            | 2055            | 8.8%                | 701                   | 21.5%                     | 29.8            | 31.7           | 78%                 | 4.9              |



### ANOVA Results Highlighting Significant Differences Across Discussion Subcategories

This table presents the F-values and significance levels for four dependent variables: sentiment score, number of comments, number of upvotes, and number of downvotes. The results indicate statistically significant differences among the discussion groups for each variable (p <0.001  ), demonstrating distinct variances in user engagement across different subcategories of discussions.

| Dependent variable |   F  | Significance   |
|--------------------|:----:|----------------|
| sentiment score    | 38.9 | <0.001         |
| comments number    |  8.5 | <0.001         |
| upvote             |  5.3 | <0.001         |
| downvote           |  8.5 | <0.001         |



### Post-hoc Analysis Using Least Significant Difference (LSD) Test Following ANOVA

This table presents multiple comparisons among subcategories within each category for four dependent variables: number of comments, upvotes, downvotes, and sentiment scores. The mean difference between subcategories (I-J) is shown, with significant differences highlighted in red. An asterisk (*) denotes statistical significance at the 0.05 level, indicating substantial disparities in user engagement and sentiment reactions between subcategories. These results provide detailed insights into the specific aspects of community interaction that are affected by varying factors.

| Multiple comparisons: LSD | Comments Number |  | Upvote |  | Downvote |  | Sentiment Score |  |
|---------------------------|-----------------|-----------------|--------|--------|----------|----------|-----------------|---------|
| (I) subcategory           | (J) subcategory | Mean difference | (J) subcategory | Mean difference | (J) subcategory | Mean difference | (J) subcategory | Mean difference |
| **1.1**                   | 1.2             | -19.9           | 1.2            | -18.9           | 1.2            | -1.5            | 1.2             | 0.1             |
|                           | 1.3             | -89.8*          | 1.3            | -212.7*         | 1.3            | -22.82*         | 1.3             | 1.8*            |
|                           | 1.4             | -3.6            | 1.4            | -24.9           | 1.4            | -2.2            | 1.4             | -0.5*           |
|                           | 1.5             | -156.2*         | 1.5            | -590.8*         | 1.5            | -45.9*          | 1.5             | 1.9*            |
|                           | 1.6             | -13.7           | 1.6            | -11.0           | 1.6            | -0.1            | 1.6             | 1.1*            |
| **1.2**                   | 1.1             | 19.9            | 1.1            | 18.9            | 1.1            | 1.5             | 1.1             | -0.1            |
|                           | 1.3             | -69.9*          | 1.3            | -193.8*         | 1.3            | -21.3*          | 1.3             | 1.7*            |
|                           | 1.4             | 16.3            | 1.4            | -5.9            | 1.4            | -0.7            | 1.4             | -0.6*           |
|                           | 1.5             | -136.3*         | 1.5            | -571.9*         | 1.5            | -44.5*          | 1.5             | 1.8*            |
|                           | 1.6             | 6.2             | 1.6            | 8.0             | 1.6            | 1.4             | 1.6             | 1.0*            |
| **1.3**                   | 1.1             | 89.9*           | 1.1            | 212.7*          | 1.1            | 22.8*           | 1.1             | -1.9*           |
|                           | 1.2             | 69.9*           | 1.2            | 193.8*          | 1.2            | 21.3*           | 1.2             | -1.7*           |
|                           | 1.4             | 86.2*           | 1.4            | 187.8*          | 1.4            | 20.7*           | 1.4             | -2.4*           |
|                           | 1.5             | -66.4*          | 1.5            | -378.1*         | 1.5            | -23.2*          | 1.5             | 0.0             |
|                           | 1.6             | 76.1*           | 1.6            | 201.7           | 1.6            | 22.7*           | 1.6             | -0.7*           |
| **1.4**                   | 1.1             | 3.6             | 1.1            | 24.9            | 1.1            | 2.2             | 1.1             | 0.5*            |
|                           | 1.2             | -16.3           | 1.2            | 5.9             | 1.2            | 0.7             | 1.2             | 0.6*            |
|                           | 1.3             | -86.2*          | 1.3            | -187.8*         | 1.3            | -20.7*          | 1.3             | 2.3*            |
|                           | 1.5             | -152.6*         | 1.5            | -565.9*         | 1.5            | -43.8*          | 1.5             | 2.4*            |
|                           | 1.6             | -10.1           | 1.6            | 13.9            | 1.6            | 2.1             | 1.6             | 1.6*            |
| **1.5**                   | 1.1             | 156.2*          | 1.1            | 590.8*          | 1.1            | 45.9*           | 1.1             | -1.9*           |
|                           | 1.2             | 136.4*          | 1.2            | 571.9*          | 1.2            | 44.5*           | 1.2             | -1.8*           |
|                           | 1.3             | 66.4*           | 1.3            | 378.1*          | 1.3            | 23.2*           | 1.3             | 0.0             |
|                           | 1.4             | 152.6*          | 1.4            | 565.9*          | 1.4            | 43.8*           | 1.4             | -2.4*           |
|                           | 1.6             | 142.5*          | 1.6            | 579.8*          | 1.6            | 45.9*           | 1.6             | -0.8*           |
| **1.6**                   | 1.1             | 13.7            | 1.1            | 11.0            | 1.1            | 0.1             | 1.1             | -1.1*           |
|                           | 1.2             | -6.2            | 1.2            | -8.0            | 1.2            | -1.4            | 1.2             | -1.0*           |
|                           | 1.3             | -76.1*          | 1.3            | -201.7          | 1.3            | -22.7*          | 1.3             | 0.7*            |
|                           | 1.4             | 10.1            | 1.4            | -13.9           | 1.4            | -2.1            | 1.4             | -1.7*           |
|                           | 1.5             | -142.5*         | 1.5            | -579.9*         | 1.5            | -45.9*          | 1.5             | 0.7*            |
| **2.1**                   | 2.2             | -10.4           | 2.2            | -28.6           | 2.2            | -1.9            | 2.2             | -0.2            |
|                           | 2.3             | -28.4*          | 2.3            | -15.5           | 2.3            | -2.5            | 2.3             | 0.5*            |
| **2.2**                   | 2.1             | 10.4            | 2.1            | 28.6            | 2.1            | 1.9             | 2.1             | 0.2             |
|                           | 2.3             | -18.0           | 2.3            | 13.1            | 2.3            | -0.6            | 2.3             | 0.6*            |
| **2.3**                   | 2.1             | 28.4*           | 2.1            | 15.5            | 2.1            | 2.5             | 2.1             | -0.5*           |
|                           | 2.2             | 18.0            | 2.2            | -13.1           | 2.2            | 0.6             | 2.2             | -0.7*           |
| **3.1**                   | 3.2             | -18.2           | 3.2            | -8.0            | 3.2            | -0.2            | 3.2             | 1.4*            |
| **3.2**                   | 3.1             | 18.2            | 3.1            | 8.0             | 3.1            | 0.2             | 3.1             | -1.4*           |
