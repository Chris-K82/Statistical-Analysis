# HOMEWORK by 12.07 10AM : 
variance/covariance formula
Good starting point : https://stats.stackexchange.com/questions/17890/what-is-the-difference-between-n-and-n-1-in-calculating-population-variance

https://www.youtube.com/user/BCFoltz/featured

    Q1: Explain the difference in the normalization constant in 
    A1: First, there are two variables which, on the surface, look the same:
    n vs. N. while n represents a sample size N reresents the poplation from
    which the sample was taken. To highlight this, let's say you want to 
    represent pedagogical statistical data from a relatively small learning
    sample onto a population of potentially infinite size. There is not way
    of understanding how large an unknown future sample might be, so the
    logical choice is to mathematically infer relational information.
    Therefore, you would compute the statistical information based on your
    sample using "n-1" in your denominator to "normalize" each data point's
    impact.

	Q2 : Explain how to compute the covariance matrix in your own words
    A2 : First, it is important to understand what covariance actually
    refers to. Covariance simply refers to a particular measure of the
    linear relationship between two variables/features.
    
    To calculate the covariance matrix, each raw score in the sample or
    population depending on which option you choose, needs to be converted
    to a deviation score based on the aggregate data within each column
    or feature. Next, we find the deviation score sums for each feature
    measured against all other features. The last step is to divide each 
    element by either n - 1 if we're using a sample or N if we are using the 
    entire population. We don't necessarily care about the individual values
    as much unless they are very near 0. We are more interested in the "sign" 
    of each value. A negative value indicates decreasing covariance whereas a 
    positive value indicates increasing covariance. And, remember, the 
    significance of this is that this is a comparison of covariance of all 
    variables to all of the other variables.
