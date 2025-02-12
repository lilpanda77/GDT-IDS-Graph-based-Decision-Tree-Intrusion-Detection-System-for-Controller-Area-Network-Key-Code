# GDT-IDS-Graph-based-Decision-Tree-Intrusion-Detection-System-for-Controller-Area-Network-Source-Code=

This repository contains the code for the GDT-IDS (Graph-based Decision Tree Intrusion Detection System), which is designed to detect various types of attacks, including spoofing and replay attacks, in in-vehicle networks using the CAN bus protocol.

**Overview**
The GDT-IDS method leverages graph theory to model the relationships between CAN messages and uses a decision tree for classification. The model is designed to handle spoofing and replay attacks effectively by introducing novel graph-based features such as time difference, betweenness centrality, and graph density. It also performs well in multi-class classification for mixed attack scenarios.

**Datasets Used**
We conduct our experiments using the following datasets:

Car-Hacking Dataset [1]
IVN Intrusion Detection Challenge Dataset [2]
Car Hacking: Attack & Defense Challenge Dataset [3]
OpelAstra Dataset [4]

These datasets provide various attack scenarios in in-vehicle networks, and the models are trained and evaluated using these data to demonstrate their effectiveness.

[1] Song, H.M., Woo, J., Kim, H.K.: In-vehicle network intrusion detection using deep convolutional neural network. Vehicular Communications 21, 100198 (2020)
[2] Han, M.L., Kwak, B.I., Kim, H.K.: Anomaly intrusion detection method for vehicular networks based on survival analysis. Vehicular communications 14, 52–63 (2018)
[3] Kang, H., Kwak, B., Lee, Y.H., Lee, H., Lee, H., Kim, H.K.: Car hacking: Attack and defense challenge 2020 dataset. IEEE Dataport (2021)
[4] Dupont, G., Lekidis, A., Hartog, J.J., Etalle, S.S.: Automotive Controller Area Network (CAN) Bus Intrusion Dataset v2. 4TU.Centre for Research Data (2019). https://doi.org/10.4121/UUID:B74B4928-C377-4585-9432-2004DFA20A5D

**Jupyter Notebook for Experiments**
We conducted our experiments using Jupyter Notebooks.
