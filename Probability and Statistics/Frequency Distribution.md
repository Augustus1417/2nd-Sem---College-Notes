##### Slovin's Formula
Determining the sample size (n)

$$
n = \frac{N}{1 + Ne^2}
$$
N = number of population
e = margin of error

**Example**:
N = 75000 | e = 2.5% or 0.025
$$
\frac{75000}{1 + (75000)(.025)^2} = 1566.58 \approx1567
$$
##### Summation Notation
$$
\sum = sum
$$
**Example**:
$$
\sum_{1}^{7} x_i = x_1 + x_2 + x_3 + x_4 + x_5 + x_6 + x_7
$$
**Example Problem:**
Given: 
$$ x_i = -3, 4, 5 $$
$$ y_i = 2, 6, 1 $$
Find:  $$\sum_{i=1}^{3} (x_i+y_i)$$
Solution: $$(-3+2)+(4+6)+(5+1) = 15$$

---
##### Frequency Distribution Table

|     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2   | 3   | 5   | 9   | 14  | 6   | 15  | 8   | 7   | 12  |
| 18  | 16  | 4   | 13  | 6   | 9   | 5   | 4   | 9   | 9   |
| 11  | 12  | 8   | 1   | 8   | 5   | 7   | 14  | 5   | 17  |
| 15  | 19  | 11  | 3   | 7   | 14  | 12  | 10  | 16  | 7   |

**Step 1:**
- Identify class size (c) and range (R)
$$K = 1 + 3.322log(n)$$
$$R = highest - lowest$$
$$c = \frac{R}{K}$$
Solution:
$$K = 1 + 3.322log(40) = 6.32$$
$$R = 19 - 1 = 18$$
$$c = \frac{18}{6.32} = 2.85 \approx{3}$$
**Step 2:**
- Identify parts:
	- *class boundary* = $$.5 - LL$$ $$.5 + UL$$
	- *class mark* = $$\frac{UL + LL}{2}$$
	- *< cumulative frequency* = sub total of frequency
	- *relative frequency* = $$\frac{frequency}{n}$$


| **class interval**<br>LL - UL | **frequency** | **class boundary** | **class mark** | **<cf** | **relative frequency** |
| ----------------------------- | ------------- | ------------------ | -------------- | ------- | ---------------------- |
| 1 - 3                         | 4             | .5 - 3.5           | 2              | 4       | 4/40 = 10%             |
| 4 - 6                         | 8             | 3.5 - 6.5          | 5              | 12      | 8/40 = 20%             |
| 7 - 9                         | 11            | 6.5 - 9.5          | 8              | 23      | 11/40 = 27.5%          |
| 10 - 12                       | 6             | 9.5 - 12.5         | 11             | 29      | 6/40 = 15%             |
| 13 - 15                       | 6             | 12.5 - 15.5        | 14             | 35      | 6/40 = 15%             |
| 16 - 18                       | 4             | 15.5 - 18.5        | 17             | 39      | 4/40 = 10%             |
| 19 - 21                       | 1             | 18.5 - 21.5        | 20             | 40      | 1/40 = 2.5%            |
|                               | n = 40        |                    |                |         | total = 100%           |
