# Sankey Diagram

* Sankey diagrams are flow diagrams where the width of the links or arrows is proportional to flow volume. For example, Sankey diagrams are commonly used to break down a budget, energy usage, or website traffic. They are useful for comparing contributions to a flow and identifying major and minor flow sources. Sometimes a picture is worth a thousand words, so scroll down to see an example Sankey diagram! This template uses Plotly to create an interactive and customizable Sankey diagram.

To use your data in this template, the following criteria must be satisfied:

* **At least two categorical columns to break down the flow. Every unique value in these columns will become a node in the diagram.**
* **A numerical column to set the width of the links between nodes (in other words: flow volume). Rows with negative or null values will be ignored.**

The placeholder data in this template consists of aggregated order data from an online store, with the total sales coming from a specific region, customer segment, and product category.

* If you have swapped your own data, review your data above to decide which categorical columns should break down the flow and in which order. You'll also have to fill out the first four steps listed in the following code cell. The rest of the code will create the Sankey diagram based on your specification!

* This plot is interactive - try moving around the nodes! You can also download it as a png using the camera icon in the top right corner. You can always experiment with a different flow order by changing the order of columns in cols. Not satisfied with the plot's colors? Revisit Step 4 in the preceding code cell.
