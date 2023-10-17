# Documentation

## Libraries Used

  1. **pandas:** Handles Table data (Loading, Saving, Modifying tables)
  2. **numpy:** Handles Matrix data (Define matrices and perform operations with them)
  3. **matplotlib.pyplot:** Plot Graph (Scatter, Surface, curve, etc.)

## Data Preprocessing

  1. **Loading the dataset into a DataFrame:** Using the pandas library we load the given dataset into a pandas DataFrame.
  2. **Normalizing the feature variable:** We normalize the feature variables by utilizing the formula: X’ = (X - μ) / σ where μ represents the mean of the feature column, and σ represents the standard deviation of the feature column.
  3. **Filling Null Values:** *-Only in Part B-* We predict the null values in cells using the mean of the existing values of the corresponding feature.
  4. **Shuffle split the dataset into training and testing sets:** We shuffle the dataset and split the dataset into training and testing sets; using 80% data for training and 20% for testing.
  
## Polynomial Regression

## Graph Plotting

### 1-A



### 1-B

## Comparative Analysis

### 1-A

### 1-B

| Q | Degree | Batch Test Error | Batch Train Error | Stochastic Test Error | Stochastic Train Error |
|----|----|------|---|---|---|
|0   |  1  | 54929.7961     | 20953.2505  | 51559.6331  | 22073.3716  |
|    |  2  | 48393.6692     | 13907.1528  | 44622.4110  | 15285.5285  |
|    |  3  | 46574.5700     | 12922.6224  | 42194.1122  | 14242.0322  |
|    |  4  | 45299.5922     | 12405.5280  | 40691.8961  | 13862.1792  |
|    |  5  | 45460.6792     | 12233.4381  | 40220.3483  | 14803.3771  |
|    |  6  | 46192.7053     | 12176.7766  | 43016.1331  | 18953.8453  |
|    |  7  | 46834.5874     | 12166.2085  | 81165.9661  | 39570.2850  |
|    |  8  | 47042.6682     | 12160.4672  | 2.5522019e+118  | 1.3328255e+118  |
|    |  9  | 46850.2169     |12150.4923  | inf  | inf  |


| Q | Degree | Batch Test Error | Batch Train Error | Stochastic Test Error | Stochastic Train Error |
|----|----|------|---|---|---|
|0.5 |  1  | 54929.7961     | 20953.2505  | 51559.6331  | 22073.3716  |
|    |  2  | 48393.6692     | 13907.1528  | 44622.4110  | 15285.5285  |
|    |  3  | 46574.5700     | 12922.6224  | 42194.1122  | 14242.0322  |
|    |  4  | 45299.5922     | 12405.5280  | 40691.8961  | 13862.1792  |
|    |  5  | 45460.6792     | 12233.4381  | 40220.3483  | 14803.3771  |
|    |  6  | 46192.7053     | 12176.7766  | 43016.133  | 18953.8453  |
|    |  7  | 46834.5874     | 12166.2085  | 81165.9661  | 39570.2850  |
|    |  8  | 47042.6682     | 12160.4672  | 2.55220e+118  | 1.332825e+118  |
|    |  9  |  46850.2169    | 12150.49231  | inf  | inf  |

| Q | Degree | Batch Test Error | Batch Train Error | Stochastic Test Error | Stochastic Train Error |
|----|----|------|---|---|---|
|1   |  1  | 54929.7961     | 20953.2505  | 51559.6331  | 22073.3716  |
|    |  2  |  48393.6692    | 13907.1528  | 44622.4110  | 15285.5285  |
|    |  3  | 46574.5700     | 12922.6224  | 42194.1122  | 14242.0322  |
|    |  4  | 45299.5922     | 12405.5280  | 40691.8961  | 13862.1792  |
|    |  5  | 45460.6792     | 12233.4381  | 40220.3483  | 14803.3771  |
|    |  6  | 46192.7053     | 12176.7766  | 43016.1331  | 18953.8453  |
|    |  7  |  46834.5874    | 12166.2085  | 81165.9661  | 39570.2850 |
|    |  8  | 47042.6682     | 12160.4672  | 2.552201e+118  | 1.332825e+118  |
|    |  9  | 46850.2169     | 12150.4923  | inf  | inf  |

| Q | Degree | Batch Test Error | Batch Train Error | Stochastic Test Error | Stochastic Train Error |
|----|----|------|---|---|---|
|2   |  1  | 54929.7961     | 20953.2505  | 51559.6331  | 22073.3716  |
|    |  2  |  48393.6692    | 13907.1528  | 44622.4110  | 15285.5285  |
|    |  3  | 46574.5700     | 12922.6224  | 42194.1122  | 14242.0322  |
|    |  4  | 45299.5922     | 12405.5280  | 40691.8961  | 13862.1792  |
|    |  5  |  45460.6792    | 12233.4381  | 40220.3483  | 14803.3771  |
|    |  6  |  46192.7053    | 12176.7766  | 43016.1331  | 18953.8453  |
|    |  7  | 46834.5874     | 12166.2085  | 81165.9661  | 39570.2850  |
|    |  8  |  47042.6682    | 12160.4672  | 2.552201e+118  | 1.332825e+118  |
|    |  9  | 46850.2169     | 12150.4923  | inf  | inf  |


| Q | Degree | Batch Test Error | Batch Train Error | Stochastic Test Error | Stochastic Train Error |
|----|----|------|---|---|---|
|4   |  1  |  54929.7961    | 20953.2505  | 51559.6331  | 22073.3716  |
|    |  2  |  48393.6692    | 13907.1528  | 44622.4110  | 15285.5285  |
|    |  3  | 46574.5700     | 12922.6224  | 42194.1122  | 14242.0322  |
|    |  4  |  45299.5922    | 12405.5280  | 40691.8961  | 13862.1792  |
|    |  5  | 45460.6792     | 12233.4381  | 40220.3483  | 14803.3771  |
|    |  6  | 46192.7053     | 12176.7766  | 43016.1331  | 18953.8453  |
|    |  7  | 46834.5874     | 12166.2085  | 81165.9661  | 39570.2850  |
|    |  8  | 47042.6682     | 12160.4672  |inf  | inf  |
|    |  9  |  inf    | inf  | inf  | inf  |



## Team Members

 1. Aryan Gupta - 2021A7PS0162H
 2. Subal Tankwal - 2021A7PS1407H