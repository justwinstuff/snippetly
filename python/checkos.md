# Check OS
Checks your OS using the platform module.
```python
import platform

if platform.system() == "Linux":
  print("You run Linux.")
elif platform.system() == "Windows":
  print("You run Windows.")
elif platform.system() == "Darwin":
  print("You run a Darwin-based OS.")
else:
  print("You run an unknown OS.")
```
