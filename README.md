Conclusions

I analyzed a tabular dataset of 569 patient observations to identify biological signals for malignancy. My audit of the variables revealed that concavity_mean is the most significant indicator, with malignant cases averaging nearly 3.5 times higher than benign cases.

The Histograms confirm this strength, specifically showing a much smaller overlap in concavity distributions compared to other features, effectively isolating the majority of the benign population near zero. My Scatter Plot further proves a positive correlation between cell size and jaggedness in malignant cells. However, it is important to note that when the radius is near 15 and the concavity is near a value of 0.1, there is a 'grey zone' or overlap between malignant and benign datapoints. In this specific range, a definitive diagnosis is harder to make based on these two features alone, requiring further clinical investigation.

Future Calculations
- Specifically for the histogram, I want to use calculus to find the area of the overlap to get a more specific number and calculation for this "grey zone"
