# Environment Setup

## Operating System

- macOS (Apple Silicon)

## Python Version

```text
Python 3.13.9
```

## Anaconda Version

```text
conda 25.11.1
```

## Setup Steps

1. Downloaded the Anaconda Distribution installer for macOS (Apple Silicon).
2. Installed Anaconda on the system.
3. Verified that Conda was accessible from the terminal.
4. Activated the base Conda environment.
5. Launched the Python interpreter.
6. Verified that commonly used data science packages (`numpy`, `pandas`, and `matplotlib`) were installed and could be imported successfully.

## Verification Commands

### Check Conda Version

```bash
conda --version
```

**Output**

```text
conda 25.11.1
```

---

### Check Available Environments

```bash
conda env list
```

**Output**

```text
# conda environments:
#
base                  *   /opt/anaconda3
```

---

### Launch Python

```bash
python
```

**Output**

```text
Python 3.13.9
```

---

### Verify Installed Packages

```python
import numpy
import pandas
import matplotlib

print("Everything works!")
```

**Output**

```text
Everything works!
```

## Proof

The following screenshots demonstrate:

- Successful Conda installation
- Active base environment
- Python interpreter launch
- Successful imports of NumPy, Pandas, and Matplotlib

# Data Organization

## Raw Data

Raw data is the original dataset collected from the source. It is stored in the `data/raw/` folder and is never edited directly. This ensures the original data remains unchanged and can always be referenced.

## Processed Data

Processed data is created by cleaning or transforming the raw data. It is stored separately in the `data/processed/` folder. This allows processed datasets to be recreated whenever necessary.

## Outputs

Outputs such as plots, reports, tables, and trained models are stored in the `outputs/` folder. Keeping outputs separate from data improves organization and prevents accidental modification of datasets.

## Data Flow

The project follows a one-directional workflow:

Raw Data → Processed Data → Outputs

Raw data is read by scripts, processed data is generated, and final outputs are produced without modifying the original data.
