---
title: "Data-Driven Prediction and Optimization of Energy Use for Transit Fleets of Electric and ICE Vehicles"
collection: publications
date: 2021-10-01
permalink: /publications/ACMTOIT2021
venue: ACM Transactions on Internet Technology, Vol. 22, No. 1, Article 7. (2021)
---

[[PDF]](https://dl.acm.org/doi/pdf/10.1145/3433992)

## Abstract
Due to the high upfront cost of electric vehicles, many public transit agencies can afford only mixed fleets
of internal combustion and electric vehicles. Optimizing the operation of such mixed fleets is challenging
because it requires accurate trip-level predictions of electricity and fuel use as well as efficient algorithms
for assigning vehicles to transit routes. We present a novel framework for the data-driven prediction of triplevel energy use for mixed-vehicle transit fleets and for the optimization of vehicle assignments, which we
evaluate using data collected from the bus fleet of CARTA, the public transit agency of Chattanooga, TN.
We first introduce a data collection, storage, and processing framework for system-level and high-frequency
vehicle-level transit data, including domain-specific data cleansing methods. We train and evaluate machine
learning models for energy prediction, demonstrating that deep neural networks attain the highest accuracy.
Based on these predictions, we formulate the problem of minimizing energy use through assigning vehicles
to fixed-route transit trips. We propose an optimal integer program as well as efficient heuristic and metaheuristic algorithms, demonstrating the scalability and performance of these algorithms numerically using
the transit network of CARTA.