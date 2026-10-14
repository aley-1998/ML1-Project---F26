# ML1-Project - F26

## Description

Given list of bank locations, how much money each one holds and the time it would take to rob each one, identify the banks to rob to make as much money as possible.

The list of banks is in `data/bank_data.csv`. This is what the data looks like.

```csv
id, x_coordinate, y_coordinate, money, time (hr)
0, 11.4, 3.3, 5000, 0.6
1, 6.9, 7.1, 15000, 0.3
2, 1.4, 13.2, 900, 1.1
```

You have **24 hours** to make as much money as possible and then escape.


```python
# example
df = pd.read_csv('bank_data.csv')
robber_algorithm(df)

# Output is a list of bank IDs
[OUTPUT] --> [664, 2341, 26, 998, 9583, 24, 1, 444, 6783]
```

You can use the `check_solution` function from `utils/check_solution.py` to test the validity of your solution and obtain a _score_.
