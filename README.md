# EDA-on-Food-Choices

1. Data Description: The dataset (food_coded.csv) contains survey responses from 125 college students regarding their eating habits, cooking frequency, food preferences, and personal details like GPA and weight.

2. Cleaning Steps:

Type Conversion: The GPA and weight columns were converted from object/string types to numeric floats.

Error Handling: Non-numeric entries (e.g., text responses in the weight column) were coerced to NaN (Not a Number) to prevent analysis errors.

3. Key Findings:

Cuisine Popularity: "Italian" and "Mexican" (or the specific top bars from your chart) are the most preferred cuisines.

GPA Distribution: Most students have a GPA between 3.0 and 3.8, with a few outliers falling below 2.5.

Lifestyle: The scatter plot examines if students who cook less (higher code value) tend to have different weights, though the correlation may be weak.
