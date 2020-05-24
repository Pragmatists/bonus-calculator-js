Bonus Calculator
================
## Build
`npm install`  
`npm run test` - run all tests  
`npm run test--collect-coverage`  - run all test with code coverage  

## Kata rules

### Individual Bonus
To calculate the bonus, you need to know the salesperson's total sales amount, their quota, their commission percentage and any tax that must be deducted.

*Examples:*

|Sales	|Quota|	Commission Percentage|	Tax Percentage | Resulting Value|
|-------|-----|----------------------|-------------------------|---|
|12000	| 11000 |	10        |			            10|		        90.0|
|12000	| 15000 |	10 |			            10|		        0.0|
|12000	| 12000|	10 |		            10|		        0.0|


### Team Bonus
A member of a sales team is entitled to a bonus if their team's total sales exceeds their team's quota.

*Examples:*

|Sales|	Quota|	Commission Percentage|	Team Members|	Resulting Value|
|-----|------|---------------------|-------------|-----------------|
|12000|	11000|	10			           | 4		       | 25.0|
|12000|	15000|	10			           | 4		       | 0.0|
|12000|	12000|	10			           | 4		       | 0.0|
|12000|	11000|	10			           | 0		       | 0.0|



