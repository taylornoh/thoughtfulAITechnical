# thoughtfulAITechnical
# Package Sorting System

This Python function sorts packages based on their volume, mass, and dimensions, dispatching them to one of three stacks:

1. **STANDARD**: Packages that are neither bulky nor heavy.
2. **SPECIAL**: Packages that are either bulky or heavy.
3. **REJECTED**: Packages that are both bulky and heavy.

## Instructions

1. The function `sort(width, height, length, mass)` takes four parameters:
   - `width` (cm)
   - `height` (cm)
   - `length` (cm)
   - `mass` (kg)
   
2. Based on the following criteria:
   - **Bulky**: Volume >= 1,000,000 cm³ or any dimension >= 150 cm.
   - **Heavy**: Mass >= 20 kg.
   
3. The function returns:
   - **"STANDARD"** if the package is neither bulky nor heavy.
   - **"SPECIAL"** if the package is either bulky or heavy.
   - **"REJECTED"** if the package is both bulky and heavy.

## Example

```python
sort(200, 200, 50, 25)  # Returns "REJECTED"
sort(100, 100, 100, 15)  # Returns "STANDARD"
```

## How to Run
1. Clone the repository.
2. Open a Python environment.
3. Run the function with the appropriate package parameters.
