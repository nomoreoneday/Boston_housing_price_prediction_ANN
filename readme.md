## Goal

Use numpy to write a neural network to complete the Boston house price prediction

## Network structure:

* l1 = Linear (X, W1, b1)
* s1 = Relu (l1)
* l2 = Linear (s1, W2, b2)
* cost = MSE (y, l2)
* Hidden layer dimension is 10

## Data

| Variables | Defination  |
|-----------|:------------:|
|CRIM       | Crime rate per capita|
|ZN         | Proportion of resident land|
|INDUS      | Proportion of non-retail commercial land|
|CHAS       | 0 or 1|
|NOX        | Nitric oxide concentration|
|RM         | Average number of rooms per house|
|AGE        | Proportion of self-use houses before 1940 |
|DIS        | Weighted distance from five Boston CBD    |
|RAD        | Convenience index from highway|
|tax        | Real estate tax rate per 10,000 US dollars in the region|
|PETATIO    | Teacher-student ratio in the area|
|B          | Proportion of black people in the region|
|LSTAT      |Proportion of low- and middle-income groups in the region|


