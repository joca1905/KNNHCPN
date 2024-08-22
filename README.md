
# KNNHCPN
Implementation of the k-nearest neighbors algorithm in colored Petri nets

![KNNHCPN_classification](https://user-images.githubusercontent.com/106780027/210082785-413ac4d3-1080-4578-bbd7-2863ed0335c3.png)
<p align="justify">
Implementation of the k-nearest neighbors algorithm for colored Petri nets using the CPN-tools software. The algorithm works for both classification and regression. It includes various functions implemented in CPN-ML and examples of applications in different databases. An excellent tool for those working with CPN-tools and discrete event systems.
</p>

**:rocket: Technologies used in the project:**

:computer: CPN Tools:  https://cpntools.org/
:memo: Version: 4.0.1

# :exclamation: **Instructions for using KNNHCPN for classification and regression:** 

- **`STEP 1:`**<p align="justify"> First, on the main page of the model, choose which activity will be performed by the algorithm (classification or regression). To do this, simply fire the transition (Choice Classification) or (Choice Regression).</p>
- **`STEP 2:`**<p align="justify"> In the CPN Tools toolbox, with the model loaded, click on the `Declarations` option. Upon clicking this item, directly below `Standard declarations`, you will find the `Config model` option to adjust the model parameters. The configurable parameters are: `k` (number of nearest neighbors), `dist` (distance used for calculations), and `norm` (boolean variable, i.e., accepts `TRUE` or `FALSE` to indicate whether data normalization will be performed). For `dist`, there are currently three available functions: `euclideanDistance`, `manhattanDistance`, and `chebyshevDistance`.</p>
- **`STEP 3:`**<p align="justify"> Enter the hierarchical network selected in Step 1, i.e., the classification or regression network. In the transitions `Load elements from test`, `Load elements training`, `x`, and `x`, adjust the links to the location on your computer where the .txt files of the training and testing databases are stored. The databases are divided into four parts: training samples, testing samples, training labels, and testing labels. Place the files in the correct locations.</p>
- **`STEP 4:`**<p align="justify"> For a faster simulation, in the toolbox, open the `Simulation` palette and press the `Fast forward` tool. You can also adjust the value of this tool to simulate a larger number of model steps.
</p>

# Authors

