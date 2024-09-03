# DOCUMENTATION

## Normalization
• Create a random 5x5 ndarray and store it to variable X. Normalize X.

This program creates a random 5x5 array and puts it through a Normalization Formula. By using a function named `np.random.random((5,5))`, using the function name `var`, this will make a 5x5 array with random values inside. To get the mean and standard deviation, `.mean()` and `.std()` was used to get mean and standard deviation, which was then used in the Normalization formula `X_normalized` which is then saved using `np.save()`. The results are then printed out, from the initial value to the normalized values.

## Divisible by 3
• Create a 10x10 Array which are the squares of the first 100 positive integers, then determine all elements that are divisible by 3.

This program creates a 10x10 array with the squares of 1 - 100, using `np.arrage()` to sort the values. The numbers are then reshaped into a 10x10 two-dimensional using `.reshape()`. The results were then saved using `np.save()` with the name of div_by_3. The results are then printed out, first printing out the squared values of 1-100 and the second results showing all values that are divisible by 3.
