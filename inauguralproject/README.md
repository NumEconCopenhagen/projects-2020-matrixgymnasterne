# Inaugural project
The intention of this project is to solve the utility maximization problem in terms of consumption and labour supply.

Firstly, the required packages are imported. With these we define the utility function as well as the constraint. We assign the wage rate 1 and use the optimize.minimize function on the negative utility.

We then plot the optimal consumption and labour in terms of the wage in an interval from 0.5 to 1.5.

In the third question the tax revenue across 10,000 individuals is calculated using the sum function.

We then redefine the parameter epsilon to 0.1 and proceed to repeat the process from question three to understand how a lower elasticity will affect the tax revenue.

Finally, we attempt to find the tax rates and the tax cutoff that will maximize the tax revenue. We use the optimize.minimize functin again, but this time with the SLSQP method (as opposed to the bounded method used previously) based on an initial guess. This returns the standard labour income tax, t0, the top bracket labour income tax, t1, and the the cut-off for the top labor income bracket, k, and the corresponding value of the tax revenue.