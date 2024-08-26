## Classification Tasks Using GPT-4

In our research, we utilized GPT-4 for three classification tasks:

1. **Filtering Out Posts Unrelated to Web3 Auditing**: The first task involved filtering out posts that were not related to Web3 auditing.
2. **Categorizing Posts by Topic**: The second task was categorizing posts related to Web3 auditing by specific topics.
3. **Assigning Sentiment Scores**: The third task involved assigning sentiment scores to relevant posts based on their content.

### Development of GPT-4 Classification Prompts

The process of developing prompts for GPT-4 classification followed these steps:

1. **Sampling and Labeling**: We randomly sampled 100 posts, which were independently labeled by two researchers. The labeling was done in groups of 10 posts.
   
2. **Comparison and Consensus**: After each group was labeled independently, the results were compared. In cases of inconsistent classifications, the researchers discussed the discrepancies until they reached a consensus, then proceeded to the next group. After 10 rounds of discussion, a consistent classification standard was established.
   
3. **Prompt Creation**: Once the classification standard was established, the researchers translated it into a prompt. The labeled sample dataset was used as a test set, and GPT-4 was employed for the classification tasks. The researchers adjusted the prompt as needed to align with the classification standard while optimizing GPT-4's performance. The final prompt was determined once GPT-4 achieved an accuracy rate of 80%.

### Validation Process

To validate GPT-4's classification work, the following steps were taken:

1. **Accuracy Validation**: After each classification task, our researchers randomly sampled 80% of the data for accuracy validation. 

2. **Iterative Improvement**: The process continued until an accuracy rate of 95% was achieved. If the accuracy requirement was not met, the prompt was redesigned until the desired accuracy was obtained.

## Classification Task Prompts

### **First Classification Task Prompt: Filtering Out Posts Unrelated to Web3 Auditing**

_“I will give you the titles and content of some Reddit posts, and you will need to use this information to determine whether they are related to Web3 auditing. First, let me tell you what Web3 auditing is._

_Web3 auditing, conducted by specialized security firms, acts as a crucial external mechanism for assessing and bolstering the security of smart contracts in Web3 applications. This process typically concludes with the public disclosure of their audited status._

_- Conducted by external, specialized security teams._
_- Focuses on the code and business logic of smart contracts._
_- Not limited to code issues but also includes broader security aspects._
_- Distinct from internal security reviews and financial audits._

_Please understand this definition, and then I will give you some examples to tell you whether these contents are related to Web3 auditing to help you learn and understand.”_



### **Second Classification Task Prompt: Categorizing Posts Related to Web3 Auditing by Topic**

_Main Category 1: Discussion of Application Audit Dynamics_

- _1.1:_ Upcoming Audits - Discussions on audits about to commence.
- _1.2:_ Ongoing Audits - Discussions on audits currently in progress.
- _1.3:_ Halted Audits - Discussions on audits that have been interrupted or canceled.
- _1.4:_ Successful Audits - Discussions on audits concluded successfully.
- _1.5:_ Failed Audits - Discussions on audits that did not meet goals or standards.
- _1.6:_ Post-Audit Attacks - Discussions on attacks faced by applications after an audit.

_Main Category 2: Direct Discussion of Web3 Auditing_

- _2.1:_ How Audits are Conducted - Discussions on methodologies and processes of audits.
- _2.2:_ Audit Firms/Auditors - Discussions on organizations or individuals conducting audits.
- _2.3:_ Impact of Audits - Discussions on the effectiveness and importance of audits.

_Main Category 3: Security Dynamics of Auditing Companies_

- _3.1:_ Security Practices of Audit Companies - Discussions on security practices in projects.
- _3.2:_ Security Knowledge of Audit Companies - Discussions on security knowledge shared by companies.

_Task: Classify the following post into one of the main categories and subcategories with one-sentence reasons. You should return your response in the following format: 'The Main Category is {number} because…; the subcategory is {number} because….'_


### **Third Classification Task Prompt: Assigning Sentiment Scores**

_Please analyze the sentiment of the text based on the title and content I provide and classify the text into one of the following five levels: 1: Very Negative, 2: Slightly Negative, 3: Neutral, 4: Slightly Positive, 5: Very Positive._
