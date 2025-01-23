Pie Chart Visualization for Waste Categorization
This code snippet generates a pie chart visualization for waste categorization, specifically showing the proportion of "Organic" and "Recyclable" waste in a dataset.

Key Features:
Data Source: The data DataFrame contains a label column, which categorizes waste into "Organic" and "Recyclable."
Visualization: The chart visually represents the percentage distribution of these categories.
Customization:
Colors: Custom colors (#a0d157 for "Organic" and #c48bb8 for "Recyclable") are applied to make the chart visually appealing.
Percentage Display: Percentages are displayed on each slice with one decimal precision, making the chart informative and easy to understand.
Code Breakdown:
data.label.value_counts():
Calculates the frequency of each category in the dataset.
Labels:
labels=['Organic', 'Recyclable']: These labels are used to identify the two categories in the chart.
Colors:
Applied to differentiate the slices corresponding to "Organic" and "Recyclable."
autopct='%1.1f%%':
Formats the chart to display the percentage distribution of the waste categories.
plt.show():
Renders the final pie chart.
Example Output:
The pie chart provides a quick, visual summary of waste distribution, which is useful for:

Environmental analysis
Waste management projects
Data reporting
