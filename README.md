# htw-data-mining-2020

# Frame the problem and look at the big picture.
- Define the objective in business terms.
Figure out who will leave the telecommunication company in the future?
- How will your solution be used?
Call the people who were clustered into "will leave soon" and talk to them.
(In our example it is: Buy the ticket or do not buy the ticket)
- What are the current solutions/workarounds (if any)?
- How should you frame this problem (supervised/unsupervised, online/offline, etc.)
- How should performance be measured?
- Is the performance measure aligned with the business objective?
- What would be the minimum performance needed to reach the business objective?
- What are comparable problems? Can you reuse experience or tools?
- Is human expertise available?
Customers do have their day to day job so they might not be available for the data collection
- How would you solve the problem manually?
- List the assumptions you or others have made so far.
- Verify assumptions if possible.

# Explore the data
Note: try to get insights from a field expert for these steps.

1. Create a copy of the data for exploration (sampling it down to a manageable size if necessary).
2. Create a Jupyter notebook to keep record of your data exploration.
3. Study each attribute and its characteristics:
- Name
- Type (categorical, int/float, bounded/unbounded, text, structured, etc.)
- % of missing values
- Noisiness and type of noise (stochastic, outliers, rounding errors, etc.)
- Possibly useful for the task?
- Type of distribution (Gaussian, uniform, logarithmic, etc.)
4. For supervised learning tasks, identify the target attribute(s).
5. Visualize the data.
6. Study the correlations between attributes.
Do not only use pearson correlation. We could have strong correlations between non correlating indicators
7. Study how you would solve the problem manually.
8. Identify the promising transformations you may want to apply.
9. Identify extra data that would be useful (go back to "Get the Data" on page 502).
10. Document what you have learned.

# Prepare the data 
- Timeseries plot and look at how the flights change
- Engineer new features!