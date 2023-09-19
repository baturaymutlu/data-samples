# Expressions Content

Sample expression for: 1 + (2 - 1)

    {
      "operator": "+", // operator can be +, -, *, /
      "operands": [
        {
          "value": 1 // leaf nodes have value only
        },
        {
          "operator": "-", // there can be nested expressions
          "operands": [
            {
              "value": 2 // leaf nodes have value only
            },
            {
              "value": 1 // leaf nodes have value only
            }
          ]
        }
      ]
    }

# Sample Expressions

* data-1: 2 * (1 + 2) + 4/2 + (4/2 - 2) = 8
* data-2: 3 * (23 - (6 / (2 / (1 + 1) + 1))) = 60
* data-3: 4 * (3 - 2) = 4