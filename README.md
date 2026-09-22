# JavaScript Statistics Toolkit

A collection of elementary statistics functions with a runnable sample dataset.

## Implemented functions

Mean, mode, median, population variance, range, and population standard deviation.

## Run

With Node.js installed:

```sh
node Statistics
```

The source file intentionally has no extension in this snapshot. Its sample array is `[1, 2, 2, 3, 4, 4, 4, 5]`.

## Expected sample results

| Metric | Value |
| --- | --- |
| Mean | 3.125 |
| Mode | 4 |
| Median | 3.5 |
| Population variance | 1.609375 |
| Range | 4 |
| Population standard deviation | Approximately 1.26861 |

Some inline output comments in [Statistics](Statistics) are rounded or inaccurate; the table above follows the implemented population formulas.

## Limitations

Empty arrays, nonnumeric inputs, and ties between multiple modes do not have explicit handling. This is an educational implementation, not a validated statistical library.

## Author

Tekena Ajuzieogu · [GitHub](https://github.com/CyberTekena)
