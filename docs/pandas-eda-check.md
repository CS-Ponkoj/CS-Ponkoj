# pandas-eda-check

[Back to Projects](../projects.md) · [Back to README](../README.md) · [PyPI](https://pypi.org/project/pandas-eda-check/) · [Repository](https://github.com/CS-Ponkoj/pandas_eda_check)

| | |
|---|---|
| **Type** | Public open-source Python package |
| **Distribution** | PyPI |
| **Status** | Tested and installable |

## Problem

Exploratory analysis repeatedly requires column-quality checks, while production data work also needs a clear view of how schema, completeness, distributions, date ranges, and categories changed between dataset versions.

## Package

`pandas-eda-check` supports both one-DataFrame inspection and reference-versus-current profile comparison.

```bash
pip install pandas-eda-check
```

```python
from pandas_eda_check import check, compare

quality_report = check(current_df, display=False)
change_report = compare(reference_df, current_df, display=False)
```

## What I Built

- `check(df)` for one-row-per-column data-quality reporting
- `compare(reference, current)` for meaningful structural, quality, and profile changes
- Schema, missing-data, duplicate-rate, numerical, datetime-range, and categorical comparisons
- Configurable thresholds and status/severity reporting
- Safe handling for empty DataFrames, nullable dtypes, mixed object values, unhashable values, infinities, and all-null columns
- DataFrame-based outputs for programmatic use
- Tests, GitHub Actions workflows, packaging metadata, and an MIT license

## Technology

Python 3.9+, pandas, pytest, PyPI packaging, GitHub Actions.

## Evidence

- [Install from PyPI](https://pypi.org/project/pandas-eda-check/)
- [Review source, tests, and documentation](https://github.com/CS-Ponkoj/pandas_eda_check)
