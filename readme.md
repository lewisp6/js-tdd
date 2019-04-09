# Setup
`npm install`

`npm test`

# Instructions

Build a Shopping cart function to calculate the total price of an array of items. The function should be able to take
two arguments, the first an array of item objects e.g:

```
[
  item1: { key: 1, price: 10.00 },
  item2: { key: 2, price: 12.00 }
]
```

The second is a boolean value named discount.

The expected output of this function is:

```
{ numberOfItems: value, total: value }
```

## Requirements

- It should give the number of items in the array and the sum of all the prices. (Example output above).

- A shipping cost should be added to the total. The standard shipping cost is £2.99.

- If discount is true then a discount of £10.00 should be applied to the total BEFORE shipping.

- If the total ends up being below 0 the final price of £0.00 plus standard shipping should be returned.

- If the total cost of the items is more than £20.00 then the shipping cost should be £0.00.

- If the total cost of the items is greater than £15 but less than £20 then the shipping cost should be £1.50
