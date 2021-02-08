# OpenStreetMap_Street_Network_Extraction
https://arxiv.org/abs/2101.09539
In this paper, we propose a smart navigation framework
intending to determine for pedestrians safe routing to bypass
areas where the risk of COVID-19 transmission is high. In
other words, the framework recommends a pedestrian walking
route in which guarantees a social distancing and avoiding
close contacts. The proposed approach includes four steps:
First, the framework identifies the IoT devices located in the
area of interest and then establishes social graphs interconnecting these devices using different social IoT relations. Then, the
Louvain community detection algorithm is applied to the SIoT
graphs to determine different communities of IoT devices. In
our approach, we focus primarily on two social relations: a
distance-based relation that identifies crowded/high-density areas of IoT devices and a device friendship relation that allows
labeling streets where the user may possess a high chance of
meeting a close friend. The third step is to compute different
scores representing each street’s safety level or segment of a
street in the area of interest according to the nearby detected
social communities. Finally, in the last step, the city map is
transformed into a weighted undirected graph to which we
apply the Dijkstra algorithm [13] in order to determine a
route characterized by a certain level of safety. A weighted
bi-objective function balancing between the shortest and safest
routes is developed and implemented. The framework will then
deliver the trajectories to the user, e.g., via a mobile application
for the best route to follow to reach a destination. The proposed
routing approach takes into account the mobility of IoT devices
and may update the recommended route regularly by repeating
the process, as mentioned earlier.
