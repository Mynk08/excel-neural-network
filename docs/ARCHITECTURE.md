# Neural Network Architecture in Excel

## Spreadsheet Layout

### Input Layer (Columns A-D)
- Cell A1: Feature 1
- Cell B1: Feature 2
- Cell C1: Feature 3
- Cell D1: Bias

### Hidden Layer (Columns F-H)
- Weighted sums: =SUMPRODUCT($A$1:$D$1, A5:D5)
- Activation: =1/(1+EXP(-F5))

### Output Layer (Column J)
- Final prediction calculation
- Activation function applied

## Weight Matrices
- Weights stored in separate sheets
- Updated through gradient descent formulas
