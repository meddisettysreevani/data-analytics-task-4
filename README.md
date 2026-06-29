# Task 4 – Data Storytelling & Statistical Validation

## Objective
Convert analytical findings into a business story and validate insights using statistical testing.

## Tools Used
- Python
- Pandas
- Matplotlib
- SciPy

## Steps Performed
1. Loaded Excel dataset.
2. Explored dataset structure.
3. Generated summary statistics.
4. Visualized:
   - Top Categories
   - Sales Distribution
5. Performed Independent T-Test.
6. Interpreted p-value.
7. Drew business conclusions.

## Business Story
- Identified top-performing categories.
- Analyzed sales distribution.
- Compared sales between two categories.
- Statistical testing determined whether the sales difference is significant.

## Hypothesis
**Null Hypothesis (H₀):**
There is no significant difference in sales between the selected categories.

**Alternative Hypothesis (H₁):**
There is a significant difference in sales between the selected categories.

## Conclusion
- If p-value < 0.05 → Reject H₀.
- If p-value ≥ 0.05 → Fail to Reject H₀.

## Libraries
- pandas
- matplotlib
- scipy

## Output
- Summary statistics
- Bar chart
- Histogram
- T-test result
- Business conclusion
