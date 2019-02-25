* mean = average
* median = middle value from sorted data
* mode = most count value

### Variance
Measeures how spread out the data is.

(1,4,5,8)
Steps:
* find the mean (1+4+5+8)/4 = 4.5
* find difference from mean (-3.5,-0.5,0.5,3.5)
* find squred difference (12.25,0.25,0.25,12.25)
* find average of squared (12.25+0.25+0.25+12.25)/4 = 6.25

### Standard deviation

square root of variance

### Population vs Sample
Population if you take all of the data points.
Sample just a subset of the dataset = sample variance (devide by total - 1)

### Normal distribution
inter quartile range (IQR) = 50% of distribution.
   
<code>np.percentile(vals, 90)</code> 90% of values are below (left) that point.

#### Moments: Measure shape of probability density function.
First moment = mean

Second moment = variance

Third moment = skew (negative or positive)

Fourth moment = How thick tail, how sharp the peak (kurtosis)

### Covariance & Correlation
#### Covariance
Measures how two variables vary in tandem from their means. How 2 variables depend on each other.
#### Correlation
-1 inverse. If one value increase, other one decreases.
0 -  No correlation
1 - Perfect correlation

<code>np.corrcoef(x,y)</code>

### Conditional Probability
What are the probability of something happening in future if something else already happened.

P(A,B) = both occurring
P(A|B) = probability of B given A has occurred

P(A|B) = P(A,B) / P(A)

### Bayes Theorem
p(A|B) = P(A)P(B|A) / P(B)

