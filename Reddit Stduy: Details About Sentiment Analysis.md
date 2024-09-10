
## Methodology for Selecting Sentiment Analysis Tools

  - We used GPT-4 to perform sentiment scoring, assigning scores from 1 (very negative) to 5 (very positive), with 3 representing neutral sentiment.
  - Two researchers independently annotated a random sample of 100 posts following strict Likert scale guidelines (1 to 5).
  - Discrepancies were resolved through discussion, and Cohen's Kappa was calculated to measure inter-rater reliability, achieving a value of 0.83, indicating substantial agreement.

- **Comparison of VADER and GPT-4**
  - VADER was selected as a comparison tool due to its widespread use in social media sentiment analysis.
  - VADER calculates sentiment scores on a scale from -1 to 1:
    - Compound scores > 0.05 indicate positive sentiment.
    - Compound scores < -0.05 indicate negative sentiment.
  - GPT-4 operates on a 5-point Likert scale (1-5).
  - To compare both systems, we mapped their results to a unified three-category sentiment scale: negative, neutral, and positive.
  - Results:
    - GPT-4 achieved an accuracy rate of 91%.
    - VADER achieved an accuracy rate of 62%.
    - Conclusion: GPT-4 significantly outperformed VADER and was selected as the primary tool for this study.

- **GPT-4 Sentiment Analysis Performance on the 1-5 Scale**
  - Overall accuracy: 92%.
  - Recall values for each sentiment level:
    - 1 (very negative): 92%.
    - 2 (slightly negative): 75%.
    - 3 (neutral): 100%.
    - 4 (slightly positive): 82%.
    - 5 (very positive): 100%.
  - GPT-4 showed a tendency to classify slightly negative posts as neutral.
    - Posts classified this way often exhibited sentiments close to neutral, leading the model to lean towards neutral classifications.
  - Conclusion: Despite some challenges with slightly negative posts, GPT-4's overall recall of 92% demonstrates strong performance in sentiment analysis.
