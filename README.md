
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
![KNNHCPN_planta](https://github.com/joca1905/KNNHCPN/blob/9622ecf604c4f60df4f5246f2ef2380682118c24/Images/Planta.png)
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

Aggarwal, C.C.: Data Classification: Algorithms and Applications vol. 1, pp. 498–501. CRC Press, New York, USA (2015)

Albuquerque, R., Júnior, C., Barroso, G., Barreto, G.: A novel fully adaptive neural network modeling and implementation using colored petri nets. Discrete Event Dynamic Systems 33, 1–32 (2023) https://doi.org/10.1007/s10626-023-00377-9

Boehmke, B., Greenwell, B.M.: Hands-On Machine Learning with R, 1st edn. Chapman and Hall/CRC, ??? (2019). https://doi.org/10.1201/9780367816377

Chan, S.M., Ke, J.S., Chang, J.F.: Knowledge representation using fuzzy petri net. IEEE Transactions on Knowledge and Data Engineering 2(3), 311–319 (1990)

Costelha, H., Lima, P.: Modelling, analysis and execution of robotic tasks using petri nets, pp. 1449–1454 (2007). https://doi.org/10.1109/IROS.2007.4399365

Cassandras, C.G., Lafortune, S.: Introduction to Discrete Event Systems, 2nd edn. Springer, Boston, MA (2008)

CPN Tools Development Group: CPN Tools. (2018). Available at http://cpntools.org

Dash, P., Naik, B., Nayak, J., Shanmuganathan, V.: Deep belief network-based probabilistic generative model for detection of robotic manipulator failure execution. Soft Computing 27 (2021) https://doi.org/10.1007/s00500-021-05572-0

Faceli, K., Lorena, A.C., Gama, J., Carvalho, A.C.P.: Inteligência Artificial: Uma Abordagem de Aprendizado de Máquina vol. 1. LTC, Rio de Janeiro (2011)

Fu, H., Xie, Y., Tu, J.-F.: Basis for deep learning model of discrete event system for information technology course design. Sens. Mater. 34(6), 2229–2241 (2022)

Grus, J.: Data Science from Scratch: First Principles with Python, 2nd edn. O’Reilly Media, Inc., Sebastopol, CA (2019)

Hastie, T., Tibshirani, R., Friedman, J.: The Elements of Statistical Learning: Data Mining, Inference, and Prediction, 2nd edn. Springer, New York, NY (2009)

Jensen, K., Kristensen, L.: Cpn ml programming (2009) https://doi.org/10.1007/b95112 3

Jensen, K., Kristensen, L., Wells, L.: Coloured petri nets and cpn tools for modelling and validation of concurrent systems. STTT 9, 213–254 (2007) https://doi.org/10.1007/s10009-007-0038-x

Keller, J.M., Gray, M.R., Givens, J.A.: A fuzzy k-nearest neighbor algorithm. IEEE Transactions on Systems, Man, and Cybernetics SMC-15(4), 580–585 (1985)

Lin, Y.-N., Hsieh, T.-Y., Yang, C.-H., Shen, V., Juang, T., Chen, W.-H.: Deep petri nets of unsupervised and supervised learning. Measurement and Control 53, 002029402092337 (2020) https://doi.org/10.1177/0020294020923375

Liu, H.C., Xu, D.H., Duan, C.Y.: Pythagorean fuzzy petri nets for knowledge representation and reasoning in large group context. IEEE Transactions on Systems, Man, and Cybernetics: Systems 51(8), 5261–5271 (2021) https://doi.org/10.1109/TSMC.2019.2949342

Mou, X., Mao, L.X., Liu, H.C., et al.: Spherical linguistic petri nets for knowledge representation and reasoning under large group environment. IEEE Transactions on Artificial Intelligence 3(3), 402–413 (2022) https://doi.org/10.1109/TAI.2022.3140282

Montgomery, D.C., Peck, E.A., Vining, G.G.: Introduction to Linear Regression Analysis, 5th edn. Wiley, Hoboken, NJ (2012)

Murata, T.: Petri nets: Properties, analysis and applications. Proceedings of the IEEE 77(4), 541–580 (1989) https://doi.org/10.1109/5.24143

Nauman, M., Akhtar, N., Alhazmi, O.H., Hameed, M., Ullah, H., Khan, N.: Improving the correctness of medical diagnostics based on machine learning with coloured petri nets. IEEE Access 9, 143434–143447 (2021) https://doi.org/10.1109/ACCESS.2021.3121092

Oliveira, Y.R.M.d., Sobrinho, A., Silva, L.D.D., Santos, D., Gorgônio, K.C., Perkusich, A.: Coloured petri nets modeling multilayer perceptron neural networks. In: 2024 IEEE International Conference on Consumer Electronics (ICCE), pp. 1–4 (2024). https://doi.org/10.1109/ICCE59016.2024.10444319

Petri, C.A.: Kommunikation mit automaten (communication with automata). Ph.D. thesis, University of Bonn (1962)

Petrosov, D.A., Lomazov, V.A., Petrosova, N.V.: Model of an artificial neural network for solving the problem of controlling a genetic algorithm using the mathematical apparatus of the theory of petri nets. Applied Sciences 11(9) (2021) https://doi.org/10.3390/app11093899

Riedmann, S., Harb, J., Hoher, S.: Timed Coloured Petri Net Simulation Model for Reinforcement Learning in the Context of Production Systems, pp. 457–465 (2021). https://doi.org/10.1007/978-3-030-78424-9_51

Salmon, A.Z.O., Foyo, P.M.G., Silva, J.R.: A formal approach to requirements engineering of automated systems: Facing the challenge for new automated systems. Journal of Control, Automation and Electrical Systems 32(4), 815–829 (2021) https://doi.org/10.1007/s40313-021-00731-y

Song, Y., Huang, J., Zhou, D., Zha, H., Giles, C.L.: Iknn: Informative k-nearest neighbor pattern classification. In: Kok, J.N., Koronacki, J., Mantaras, R., Matwin, S., Mladenic, D., Skowron, A. (eds.) Knowledge Discovery in Databases: PKDD 2007, pp. 248–264. Springer, Berlin, Heidelberg (2007)

Witten, I.H., Frank, E., Hall, M.A.: Data Mining: Practical Machine Learning Tools and Techniques vol. 3, 3rd edn. Elsevier, Burlington, MA (2011)

Zhou, J.: A fuzzy petri-net approach for fault analysis considering factor influences. IEEE Access 8, 72229–72238 (2020) https://doi.org/10.1109/ACCESS.2020.2986306

<!--
# Citation

If this repository helps you in any way, consider citing our paper as follows:

```bibtex
@unpublished{moura2024knn,
  author    = {Joaquim Moura and Vanessa Vieira and Giovanni Barroso and George A. P. Thé and Márcio Amora},
  title     = {Development and Modeling of the K-Nearest Neighbors Algorithm Using Coloured Petri Nets},
  note      = {In preparation},
  year      = {2024},
  organization = {Federal University of Ceará},
}
