# Lecture 24: Selection Analytics – 2

Human Resource (HR) Analytics involves using data and analytical processes to understand, improve, and make decisions about HR practices and policies. Here’s an overview of the content you provided, with explanations on the different aspects of HR analytics:

### 1. **Consequences of Cut Scores**

A **cut score** is a threshold set by organizations to determine whether a candidate passes or fails a selection test. Setting the appropriate cut score is crucial because it impacts the quality of hires and the overall effectiveness of the selection process. 

- **True Positives (Successful Hire)**: Candidates who are correctly identified as suitable for the job.
- **False Negatives (Unsuccessful Hire)**: Candidates who are mistakenly rejected despite being suitable for the job.
- **True Negatives (Correct Rejection)**: Candidates who are correctly identified as unsuitable for the job.
- **False Positives (Unsuccessful Hire)**: Candidates who are mistakenly selected despite being unsuitable for the job.

The selection outcomes based on these definitions can be summarized in a table format:

| Actual Performance of Potential Candidate | Good Performance | Poor Performance |
|-------------------------------------------|------------------|------------------|
| **Selected**                              | True Positives (A) | False Positives (B) |
| **Not Selected**                          | False Negatives (C) | True Negatives (D) |

### 2. **Outcome of the Selection Process**

The outcome of the selection process is often assessed by analyzing the match between the predicted and actual performance of candidates. This helps HR teams understand the effectiveness of their selection tools and make adjustments as needed to improve the process.

- **Successful Selections**: Instances where the predicted and actual outcomes align positively (True Positives and True Negatives).
- **Unsuccessful Selections**: Instances where there is a mismatch between predicted and actual outcomes (False Positives and False Negatives).

### 3. **Quality of Hire**

**Quality of Hire** is a metric that measures the value a new hire brings to an organization. It's a composite score that typically includes several performance indicators:

- **PR (Performance Review Rating)**: The average performance review rating of new hires, which evaluates how well new hires perform in their roles.
- **HP (Hiring Productivity)**: The percentage of new hires who reach acceptable productivity levels within a prescribed time period.
- **HR (Hiring Retention)**: The percentage of new hires retained after one year of employment.

The formula for calculating the Quality of Hire is:

\[
\text{Quality of Hire} = \frac{(\text{PR} + \text{HP} + \text{HR})}{3}
\]

This metric helps organizations evaluate the overall effectiveness of their hiring process and identify areas for improvement.

### 4. **Cost Per Joinee**

**Cost per Joinee** is a metric that calculates the total cost associated with hiring each new employee. This includes all expenses related to recruitment, such as advertising, agency fees, travel expenses for interviews, and onboarding costs.

To calculate the Cost per Joinee, you can use the formula:

\[
\text{Cost per Joinee} = \frac{\text{Total Hiring Costs}}{\text{Number of Joinees}}
\]

Here's an example breakdown of this metric over a year:

| **Year** | **Cost per Joinee** | **Joinees (Number)** | **Total Cost** |
|----------|---------------------|----------------------|----------------|
| Year 1   | $5,000              | 20                   | $100,000       |
| Year 2   | $6,000              | 25                   | $150,000       |

By analyzing these costs, HR departments can manage their budgets more effectively and optimize recruitment processes.

### Conclusion

These HR analytics metrics are essential tools for measuring and improving the recruitment and selection process. By using data to understand the consequences of cut scores, assess the quality of hires, and calculate costs, organizations can make informed decisions that enhance their workforce and drive business success.


Let’s create a detailed dummy example and calculate the various HR analytics metrics step-by-step.

### Dummy Scenario for Calculation

**Company:** ABC Tech  
**Position:** Data Analyst  
**Number of Candidates Applied:** 200  
**Number of Candidates Selected for Interviews:** 100  
**Number of Candidates Hired:** 50  
**Performance Review Rating (PR) of Hired Candidates:** Measured on a scale of 1 to 5  
**Productivity Level Achievement (HP):** Measured as the percentage of new hires reaching acceptable productivity levels within the first 6 months  
**Retention Rate (HR):** Measured as the percentage of new hires retained after one year

### Step-by-Step Calculations

#### 1. **Consequences of Cut Scores**

Assume the company sets a cut score of 75 for the aptitude test:

- **True Positives (TP):** 30 candidates scored above 75, were hired, and performed well.
- **False Positives (FP):** 10 candidates scored above 75, were hired, but underperformed.
- **True Negatives (TN):** 70 candidates scored below 75 and were correctly not hired.
- **False Negatives (FN):** 10 candidates scored below 75 but could have performed well if hired.

##### **Table of Outcomes Based on Cut Scores:**

| Actual Performance of Potential Candidate | Good Performance | Poor Performance |
|-------------------------------------------|------------------|------------------|
| **Selected (Score ≥ 75)**                 | 30 (TP)          | 10 (FP)          |
| **Not Selected (Score < 75)**             | 10 (FN)          | 70 (TN)          |

- **Calculation:**  
  - **True Positive Rate (TPR):** \( \frac{\text{TP}}{\text{TP} + \text{FN}} = \frac{30}{30 + 10} = 0.75 \)  
  - **False Positive Rate (FPR):** \( \frac{\text{FP}}{\text{FP} + \text{TN}} = \frac{10}{10 + 70} = 0.125 \)

#### 2. **Outcome of the Selection Process**

Using the same dummy data, let’s evaluate the selection process outcomes:

- **Selected Candidates:** 50 (30 Good Performance, 20 Poor Performance)
- **Non-Selected Candidates:** 150 (10 Good Performance, 140 Poor Performance)

##### **Table of Outcomes for Selection Process:**

| Actual Performance of Potential Candidate | Good Performance | Poor Performance |
|-------------------------------------------|------------------|------------------|
| **Selected**                              | 30 (A)           | 20 (B)           |
| **Not Selected**                          | 10 (C)           | 140 (D)          |

- **Calculation:**  
  - **Accuracy of Selection:** \( \frac{A + D}{A + B + C + D} = \frac{30 + 140}{30 + 20 + 10 + 140} = \frac{170}{200} = 0.85 \)

#### 3. **Quality of Hire**

For the 50 hired candidates, let’s assume the following:

- **Performance Review Rating (PR):** The average rating is 4.0 out of 5.
- **Productivity Level Achievement (HP):** 80% of new hires reached acceptable productivity levels within the first 6 months.
- **Retention Rate (HR):** 70% of new hires were retained after one year.

##### **Calculation of Quality of Hire:**

\[
\text{Quality of Hire} = \frac{(\text{PR} + \text{HP} + \text{HR})}{3}
\]

Substitute the values:

\[
\text{Quality of Hire} = \frac{(4.0 + 80 + 70)}{3} = \frac{154}{3} = 51.33
\]

#### 4. **Cost Per Joinee**

Let’s assume ABC Tech has the following recruitment costs over a year:

- **Year 1:**
  - **Total Hiring Costs:** $200,000
  - **Number of Joinees:** 50

- **Year 2:**
  - **Total Hiring Costs:** $250,000
  - **Number of Joinees:** 60

##### **Calculation of Cost Per Joinee:**

\[
\text{Cost per Joinee (Year 1)} = \frac{200,000}{50} = 4,000
\]

\[
\text{Cost per Joinee (Year 2)} = \frac{250,000}{60} = 4,167
\]

### Summary of Calculations

1. **Consequences of Cut Scores:**
   - **True Positive Rate (TPR):** 75%
   - **False Positive Rate (FPR):** 12.5%

2. **Outcome of Selection Process:**
   - **Accuracy of Selection:** 85%

3. **Quality of Hire:**
   - **Quality of Hire Score:** 51.33 (out of 100)

4. **Cost Per Joinee:**
   - **Year 1:** $4,000
   - **Year 2:** $4,167

### Conclusion

These detailed calculations using dummy data provide a clear example of how HR analytics metrics can be calculated and used to evaluate and improve the hiring process. By understanding these metrics, organizations like ABC Tech can make informed decisions to optimize their recruitment strategies, improve hire quality, and manage costs effectively.