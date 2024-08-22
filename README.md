# mchange - Fast and Free currency converter that uses Xe.
## How to use

First, install a **mchange** package:
```shell
python -m pip install mchange
```

## Code Examples

```python
import mchange

converted = mchange.change(1, Currency.USD, Currency.MDL) # First - Quantity to be changed; Second - From; Third - To.
print(converted)
```

In this example, we found out the exchange rate of 1 dollar in Moldovan lei
All currencies are stored in the 'Currency' class.
