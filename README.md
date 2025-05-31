
# KNNHCPN
Implementation of the k-nearest neighbors algorithm in colored Petri nets

![KNNHCPN_classification](https://github.com/joca1905/KNNHCPN/blob/9622ecf604c4f60df4f5246f2ef2380682118c24/Images/Classification_ing.png)
<p align="justify">
Implementation of the k-nearest neighbors algorithm for colored Petri nets using the CPN-tools software. The algorithm works for both classification and regression. It includes various functions implemented in CPN-ML and examples of applications in different databases. An excellent tool for those working with CPN-tools and discrete event systems.
</p>

**:rocket: Technologies used in the project:**

:computer: CPN Tools: https://cpntools.org/
:memo: Version: 4.0.1

# ⚙️ **Implementation Features** 

- **Applicable to Both Classification and Regression:** <p align="justify">The KNN algorithm implemented in coloured Petri nets (KNNHCPN) is suitable for addressing both classification and regression problems.</p>

- **Graphical Visualization:** <p align="justify"> The model in Petri nets provides a graphical visualization of the KNN algorithm, making the modeling process straightforward and user-friendly.</p>

- **Fully Adaptable Implementation:** <p align="justify"> The proposed method offers a fully adaptable implementation and can be used with any set of numerical data.</p>

- **Versatile Application:** <p align="justify"> This implementation is ideal for modeling discrete systems, supporting the development of a variety of new applications.</p>

# :exclamation: **Instructions for using KNNHCPN for classification and regression:** 
- **`STEP 1:`**<p align="justify"> Open the CPN tools and in the toolbox open the **NET** palette, then click on the **Load net** option and load the `knn_iris_ing.cpn` model.</p>
- **`STEP 2:`**<p align="justify"> On the main page of the model, choose which activity will be performed by the algorithm (classification or regression). To do this, simply fire the transition (Choice Classification) or (Choice Regression).</p>
- **`STEP 3:`**<p align="justify"> In the CPN Tools toolbox, with the model loaded, click on the `Declarations` option. Upon clicking this item, directly below `Standard declarations`, you will find the `Config model` option to adjust the model parameters. The configurable parameters are: `k` (number of nearest neighbors), `dist` (distance used for calculations), and `norm` (boolean variable, i.e., accepts `TRUE` or `FALSE` to indicate whether data normalization will be performed). For `dist`, there are currently three available functions: `euclideanDistance`, `manhattanDistance`, and `chebyshevDistance`.</p>
- **`STEP 4:`**<p align="justify"> Enter the hierarchical network selected in Step 2, i.e., the classification or regression network. In the transitions `Load elements from test`, `Load elements training`, `Load test labels`, and `Load training labels`, adjust the links to the location on your computer where the .txt files of the training and testing databases are stored. The databases are divided into four parts: training samples, testing samples, training labels, and testing labels. Place the files in the correct locations.</p>
- **`STEP 5:`**<p align="justify"> For a faster simulation, in the toolbox, open the `Simulation` palette and press the `Fast forward` tool. You can also adjust the value of this tool to simulate a larger number of model steps.
</p>

# :bulb: **Simulation of discrete event systems** 
![KNNHCPN_planta](https://github.com/joca1905/KNNHCPN/blob/main/Images/planta.png)
<p align="justify">
The KNNHCPN opens up new possibilities for the modeling of discrete event systems, and it can be integrated into other models to perform classification and regression tasks.
</p>

# 📁 Applied Datasets

| **Dataset**                                    | **Description**                                                                                                                                                               |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Iris**                                       | Available at [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)  |
| **Breast Cancer Wisconsin (BCW)**              | Available at [BCW Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) |
| **Adult**                                      | Available at [Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)      |
| **Wine**                                       | Available at [Wine Dataset](https://archive.ics.uci.edu/ml/datasets/wine)                           |
| **Abalone**                                    | Available at [Abalone Dataset](https://archive.ics.uci.edu/ml/datasets/abalone) |
| **Computer Hardware**                           | Available at [Computer Hardware Dataset](https://archive.ics.uci.edu/ml/datasets/Computer+Hardware) |
| **Air Quality UCI**                            | Available at [Air Quality UCI Dataset](https://archive.ics.uci.edu/ml/datasets/Air+Quality) |
| **Concrete Compressive Strength (CCS)**        | Available at [CCS Dataset](https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength) |
| **Robot Execution Failures (REF)**        | Available at [REF Dataset](https://archive.ics.uci.edu/dataset/138/robot+execution+failures) |
<!--
# Authors

<!--
<table>
  <tr>
    <td>
      <img src="https://github.com/joca1905/KNNHCPN/blob/9622ecf604c4f60df4f5246f2ef2380682118c24/Images/Joaquim.jpg" alt="foto_joaquim" width="150"/>
    </td>
    <td>
      <strong>Joaquim Osterwald Frota Moura Filho</strong><br>
      <sub>PhD student at PPGETI, Federal University of Ceará</sub>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/joca1905/KNNHCPN/blob/1c15b254dbb96ee0a7937a4e7fa6f9f46666c97a/Images/van.jpg" alt="foto_vanessa" width="150"/>
    </td>
    <td>
      <strong>Vanessa Vieira de Sousa </strong><br>
      <sub>PhD student at PPGETI, Federal University of Ceará</sub>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/joca1905/KNNHCPN/blob/9622ecf604c4f60df4f5246f2ef2380682118c24/Images/Giovanni.jpeg" alt="foto_gio3" width="150"/>
    </td>
    <td>
      <strong>Giovanni Cordeiro Barroso</strong><br>
      <sub>Full professor at the Federal University of Ceará</sub>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/joca1905/KNNHCPN/blob/9622ecf604c4f60df4f5246f2ef2380682118c24/Images/George.jpeg" alt="foto_george" width="150"/>
    </td>
    <td>
      <strong>George André Pereira Thé</strong><br>
      <sub>Professor at the Federal University of Ceará</sub>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/joca1905/KNNHCPN/blob/9622ecf604c4f60df4f5246f2ef2380682118c24/Images/Amora.jpeg" alt="foto_amora" width="150"/>
    </td>
    <td>
      <strong>Márcio André Baima Amora</strong><br>
      <sub>Associate professor I at the Federal University of Ceará, Sobral Campus</sub>
    </td>
  </tr>
</table>
-->


# References

Aeberhard, S., & Forina, M. (1992). Wine. UCI Machine Learning Repository. https://doi.org/10.24432/C5PC7J  

Aggarwal, C. C. (2015). *Data Classification: Algorithms and Applications* (Vol. 1, pp. 498–501). CRC Press.  

Albuquerque, R., Júnior, C., Barroso, G., & Barreto, G. (2023). A novel fully adaptive neural network modeling and implementation using colored petri nets. *Discrete Event Dynamic Systems, 33*, 1–32. https://doi.org/10.1007/s10626-023-00377-9  

Becker, B., & Kohavi, R. (1996). Adult. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20  

Boehmke, B., & Greenwell, B. M. (2019). *Hands-On Machine Learning with R* (1st ed., p. 484). Chapman and Hall/CRC. https://doi.org/10.1201/9780367816377  

Cassandras, C. G., & Lafortune, S. (2008). *Introduction to Discrete Event Systems* (2nd ed.). Springer.  

Chan, S. M., Ke, J. S., & Chang, J. F. (1990). Knowledge representation using fuzzy petri net. *IEEE Transactions on Knowledge and Data Engineering, 2*(3), 311–319.  

Costelha, H., & Lima, P. (2007). Modelling, analysis and execution of robotic tasks using petri nets (pp. 1449–1454). https://doi.org/10.1109/IROS.2007.4399365  

CPN Tools Development Group. (2018). *CPN Tools*. http://cpntools.org  

Dash, P., Naik, B., Nayak, J., & Shanmuganathan, V. (2021). Deep belief network-based probabilistic generative model for detection of robotic manipulator failure execution. *Soft Computing, 27*. https://doi.org/10.1007/s00500-021-05572-0  

Faceli, K., Lorena, A. C., Gama, J., & Carvalho, A. C. P. (2011). *Inteligência Artificial: Uma Abordagem de Aprendizado de Máquina* (Vol. 1). LTC.  

Feldmesser, J. (1987). Computer Hardware. UCI Machine Learning Repository. https://doi.org/10.24432/C5830D  

Fisher, R. A. (1936). Iris. UCI Machine Learning Repository. https://doi.org/10.24432/C56C76  

Fu, H., Xie, Y., & Tu, J.-F. (2022). Basis for deep learning model of discrete event system for information technology course design. *Sens. Mater., 34*(6), 2229–2241.  

Grus, J. (2019). *Data Science from Scratch: First Principles with Python* (2nd ed.). O’Reilly Media.  

Hastie, T., Tibshirani, R., & Friedman, J. (2009). *The Elements of Statistical Learning: Data Mining, Inference, and Prediction* (2nd ed.). Springer.  

Hinojosa Herrera, A., Walshaw, C., & Bailey, C. (2020). Improving black box classification model veracity for electronics anomaly detection (pp. 1092–1097). https://doi.org/10.1109/ICIEA48937.2020.9248258  

Huang, S., Huang, M., & Lyu, Y. (2019). A novel approach for sand liquefaction prediction via local mean-based pseudo nearest neighbor algorithm and its engineering application. *Advanced Engineering Informatics, 41*, 100918.  

Jensen, K., & Kristensen, L. (2009). CPN ML programming. https://doi.org/10.1007/b95112_3  

Jensen, K., Kristensen, L., & Wells, L. (2007). Coloured petri nets and CPN tools for modelling and validation of concurrent systems. *STTT, 9*, 213–254. https://doi.org/10.1007/s10009-007-0038-x  

Jensen, K., Christensen, S., & Kristensen, L. M. (2002). *CPN Tools State Space Manual*. University of Aarhus. https://cpntools.org/wp-content/uploads/2018/01/manual.pdf  

Keller, J. M., Gray, M. R., & Givens, J. A. (1985). A fuzzy k-nearest neighbor algorithm. *IEEE Transactions on Systems, Man, and Cybernetics, SMC-15*(4), 580–585.  

KNNHCPN Team. (2024). *KNNHCPN*. GitHub repository. https://github.com/joca1905/KNNHCPN.git  

Lin, Y.-N., Hsieh, T.-Y., Yang, C.-H., Shen, V., Juang, T., & Chen, W.-H. (2020). Deep petri nets of unsupervised and supervised learning. *Measurement and Control, 53*. https://doi.org/10.1177/0020294020923375  

Liu, H. C., Xu, D. H., & Duan, C. Y. (2021). Pythagorean fuzzy petri nets for knowledge representation and reasoning in large group context. *IEEE Transactions on Systems, Man, and Cybernetics: Systems, 51*(8), 5261–5271. https://doi.org/10.1109/TSMC.2019.2949342  

Lopes, L., & Camarinha-Matos, L. (1998). Robot Execution Failures. UCI Machine Learning Repository. https://doi.org/10.24432/C5M89N  

Luo, J., Yi, S., Lin, Z., Zhang, H., & Zhou, J. (2024). Petri-net-based deep reinforcement learning for real-time scheduling of automated manufacturing systems. *Journal of Manufacturing Systems, 74*, 995–1008. https://doi.org/10.1016/j.jmsy.2024.05.006  

Montgomery, D. C., Peck, E. A., & Vining, G. G. (2012). *Introduction to Linear Regression Analysis* (5th ed.). Wiley.  

Mou, X., Mao, L. X., Liu, H. C., et al. (2022). Spherical linguistic petri nets for knowledge representation and reasoning under large group environment. *IEEE Transactions on Artificial Intelligence, 3*(3), 402–413. https://doi.org/10.1109/TAI.2022.3140282  

Murata, T. (1989). Petri nets: Properties, analysis and applications. *Proceedings of the IEEE, 77*(4), 541–580. https://doi.org/10.1109/5.24143  

Nauman, M., Akhtar, N., Alhazmi, O. H., Hameed, M., Ullah, H., & Khan, N. (2021). Improving the correctness of medical diagnostics based on machine learning with coloured petri nets. *IEEE Access, 9*, 143434–143447. https://doi.org/10.1109/ACCESS.2021.3121092  

Nash, W., Sellers, T., Talbot, S., Cawthorn, A., & Ford, W. (1994). Abalone. UCI Machine Learning Repository. https://doi.org/10.24432/C55C7W  

Oliveira, Y. R. M., Sobrinho, Á., Silva, L. D., Santos, D., Gorgônio, K. C., & Perkusich, A. (2024). Coloured petri nets modeling multilayer perceptron neural networks. *2024 IEEE International Conference on Consumer Electronics (ICCE)* (pp. 1–4). https://doi.org/10.1109/ICCE59016.2024.10444319  

Petri, C. A. (1962). *Kommunikation mit Automaten* [PhD thesis]. University of Bonn.  

Petrosov, D. A., Lomazov, V. A., & Petrosova, N. V. (2021). Model of an artificial neural network for solving the problem of controlling a genetic algorithm using the mathematical apparatus of the theory of petri nets. *Applied Sciences, 11*(9). https://doi.org/10.3390/app11093899  

Riedmann, S., Harb, J., & Hoher, S. (2021). Timed Coloured Petri Net Simulation Model for Reinforcement Learning in the Context of Production Systems (pp. 457–465). https://doi.org/10.1007/978-3-030-78424-9_51  

Salmon, A. Z. O., Foyo, P. M. G., & Silva, J. R. (2021). A formal approach to requirements engineering of automated systems: Facing the challenge for new automated systems. *Journal of Control, Automation and Electrical Systems, 32*(4), 815–829. https://doi.org/10.1007/s40313-021-00731-y  

Silveira, A. C. M., Sobrinho, Silva, L. D., Santos, D. F. S., Nauman, M., & Perkusich, A. (2025). Harnessing coloured petri nets to enhance machine learning: A simulation-based method for healthcare and beyond. *Simulation Modelling Practice and Theory, 140*, 103080. https://doi.org/10.1016/j.simpat.2025.103080  

Song, Y., Huang, J., Zhou, D., Zha, H., & Giles, C. L. (2007). IKNN: Informative k-nearest neighbor pattern classification. In J. N. Kok et al. (Eds.), *Knowledge Discovery in Databases: PKDD 2007* (pp. 248–264). Springer.  

Vandenabeele, J., Vermaut, G., Peeperkorn, J., & Weerdt, J. (2022). Enhancing stochastic petri net-based remaining time prediction using k-nearest neighbors. *Proceedings CEUR Workshop, 3167*, 9–24. https://doi.org/10.48550/arXiv.2206.13109  

Vito, S. (2008). Air Quality. UCI Machine Learning Repository. https://doi.org/10.24432/C59K5F  

Wang, X., Yu, W., Ding, Z., Zhai, X., & Saha, S. (2022). Modeling and analyzing of breast tumor deterioration process with petri nets and logistic regression. *Complex System Modeling and Simulation, 2*, 264–272. https://doi.org/10.23919/CSMS.2022.0016  

Witten, I. H., Frank, E., & Hall, M. A. (2011). *Data Mining: Practical Machine Learning Tools and Techniques* (3rd ed.). Elsevier.  

Wolberg, W. H., Mangasarian, O. L., Street, N., & Street, W. (1993). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B  

Yeh, I.-C. (1998). Concrete Compressive Strength. UCI Machine Learning Repository. https://doi.org/10.24432/C5PK67  

Zhou, J. (2020). A fuzzy petri-net approach for fault analysis considering factor influences. *IEEE Access, 8*, 72229–72238. https://doi.org/10.1109/ACCESS.2020.2986306  

--
# Citation

If this repository helps you in any way, consider citing our paper as follows:

```bibtex
@article{Filho2025,
  author = {Filho, Joaquim O. F. Moura and Sousa, Vanessa V. and Thé, George A. P. and Amora, Márcio A. B. and Barroso, Giovanni C.},
  title = {Development and Modeling of the K-Nearest Neighbors Algorithm Using Coloured Petri Nets},
  journal = {Journal of Control, Automation and Electrical Systems},
  year = {2025},
  volume = {},
  number = {},
  pages = {},
  doi = {10.1007/s40313-025-01176-3},
  url = {https://doi.org/10.1007/s40313-025-01176-3},
  issn = {2195-3899},
  abstract = {The K-nearest neighbor algorithm is among the most widely used methods for classification and regression problems in machine learning and is preferred over many other methods because of its simplicity and availability as a tool in many open-source software libraries. Despite its importance, it is usually offered as an implementation with limited insights into the algorithm steps, which can lead researchers to miss valuable comprehension about the intrinsic details of the method itself. To mitigate this, we introduce a K-Nearest Neighbor (KNN) model implementation that relies on colored Petri nets to enhance the understanding and graphical visualization of the algorithm. The proposed approach uses CPN Tools for modeling the KNN algorithm and conducting tests with various recognized classification and regression datasets from the literature. The model was validated via a comparison with a Python KNN implementation using the Scikit-learn library. An application example of dynamic system modeling is presented in the context of fault detection for robotic manipulators. The results showed that the proposed implementation achieved performance equivalent to the Python implementation and that it allows for a detailed diagnosis, enabling greater understanding and highlighting the relevant steps of the operation of complex discrete event systems.}
}

