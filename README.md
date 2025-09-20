# python-excel-project-sp-
import pandas as pd

# Simple Excel + Python project
df = pd.DataFrame({
    "Numbers": [10, 20, 30, 40, 50]
})

print("Summary:")
print(df.describe())

# Save to Excel
df.to_excel("output.xlsx", index=False)

