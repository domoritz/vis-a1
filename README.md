# Visualization Assignment 1

Check it out at https://domoritz.github.com/vis-a1.

# Description

My visualization shows the efficiency of three antibiotics based on Burtin's antibiotics data. For each bacterium in the dataset, it shows the effectiveness measured as the inverted minimum inhibitory concentration (MIC). The bacteria are grouped by gram negative and gram positive. I decided to use a horizontal bar chart for each antibiotic. Grouping by bacterium would have made it difficult to compare effectiveness of an antibiotic. A horizontal visualization used the space more efficiently (a visualization that is wider that high usually fits better).

With my visualization, I want to show how effective an antibiotic is against the different kinds of bacteria. I decided to use the reversed log10 of the MIC as a measure of efficiency of the antibiotic. In order to make it obvious that the scale is a log scale, I added ticks to the x-axis. Gram negative and gram positive bacteria are grouped together. The colors purple-blue and pink-red are the resulting colors when using gram staining to distinguish bacterial species. On the right, I added labels for gram negative and gram positive bacteria in the appropriate colors.

In my visualization, one can observe that penicillin is not very effective when applied to gram negative bacteria. Within each group the bacteria is sorted alphabetic which (due to the naming) groups families of bacteria (i.e. Streptococcus) together. One interesting observation that can be made is that "Diplococcus pneumoniae" has a pattern (resistant to Streptomycin and Neomycin) similar to Streptococcus. Interestingly, Wikipedia says that it was renamed "Streptococcus pneumoniae" in 1974. My visualization does not highlight bacteria families further because of possible incorrectnesses.

I added vertical grid lines to visually guide the user. The background of each antibiotic chart is darker to visually group the bars for each antibiotic. Small numbers on each bar show exact MICs to allow the viewer to make qualitative comparisons, which are typically difficult when log scales are used. I think that my visualization effectively shows the efficiency of the three antibiotics when applied to different families of bacteria. I avoided visual clutter, provided enough details to understand the efficiency and used the space well.