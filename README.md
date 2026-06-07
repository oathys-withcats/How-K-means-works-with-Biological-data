K-means Clustering Explorer
An interactive web application for teaching and learning the K-means clustering algorithm, built with leaf morphometric data (30 specimens, leaf length × leaf width).
Features

Step-by-step algorithm visualization — walk through initialization, assignment, and centroid update phases one step at a time, or run to convergence instantly.
Live distance calculation — hover over any data point to see Euclidean distances to all centroids. Toggle the "Distances" checkbox to display assignment lines for all points simultaneously.
Adjustable k — switch between k = 2, 3, 4, or 5 clusters and observe how results change.
Elbow method — a dedicated tab plots total within-cluster sum of squares (WSS) for k = 1–8 to demonstrate optimal cluster selection.
Data table — view raw specimen data alongside cluster assignments and distances to centroids after running the algorithm.
Calculation log — a running log records every initialization, assignment, centroid update, and convergence event with numeric detail.
Metric dashboard — real-time display of iteration count, total WSS, cluster sizes, and convergence status.

Dataset
SpecimenLeaf length (cm)Leaf width (cm)L01–L082.4 – 4.52.3 – 4.5L09–L104.8 – 5.35.1 – 6.2L11–L206.7 – 8.85.4 – 8.6L21–L295.6 – 8.92.2 – 4.7L305.97.4
30 specimens spanning three apparent morphotypes: small leaves (short and narrow), large-broad leaves (long and wide), and long-narrow leaves (long but narrow).
