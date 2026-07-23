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
