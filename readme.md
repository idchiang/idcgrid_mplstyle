1. Locate the directory of matplotlib sytles by:

```python3
import matplotlib as mpl
mpl.get_configdir()
```

2. Copy the stylelib file to that directory.

3. Refresh the concole.

4. To use the style, do:

```python3
import matplotlib.pyplot as plt
plt.style.use("idcgrid")
```
