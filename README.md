# SensorBuster
This repository contains dataset used in "SensorBuster: On Identifying Sensor Nodes in P2P Botnets"

Sality
=======
1. The files _SalityV3-##.gv_ are the pseudonymized snapshots of the Sality botnet at the lowest population of each of the seven days in our dataset.

2. The files _SalityV3-##-Uptime.txt_ contain the uptimes of the nodes calculated based on their responses to Hello messages.

Mapping from ## to Date and Time (For Sality):

  2: 08/10/2015 02:00:00-02:59:59 UTC 
 26: 09/10/2015 02:00:00-02:59:59 UTC 
 50: 10/10/2015 02:00:00-02:59:59 UTC 
 74: 11/10/2015 02:00:00-02:59:59 UTC 
 98: 12/10/2015 02:00:00-02:59:59 UTC 
122: 13/10/2015 02:00:00-02:59:59 UTC 
146: 14/10/2015 02:00:00-02:59:59 UTC 

ZeroAccess (ZA)
===============
1. The files _ZA71-##.gv_ are the pseudonymized snapshots of the ZeroAccess botnet at the lowest population of each of the seven days in our dataset.

2. The files _ZA71-##-HourlyUptime.txt_ contain the uptimes of the ZA71 nodes based on the NL-exchange messages.

Mapping from ## to Date and Time (For ZA):

  5: 07/11/2015 05:00:00-05:59:59 UTC
 29: 08/11/2015 05:00:00-05:59:59 UTC
 53: 09/11/2015 05:00:00-05:59:59 UTC
 77: 10/11/2015 05:00:00-05:59:59 UTC
101: 11/11/2015 05:00:00-05:59:59 UTC
125: 12/11/2015 05:00:00-05:59:59 UTC
149: 13/11/2015 05:00:00-05:59:59 UTC

General
=======
1. The Files _ZA71FP_,_ZA71TP_,_SalityV3FP_ and _SalityV3TP_ contain the hashes of the nodes we identified as our ground truth for the evaluation.

Citing
======
If you are using our dataset, please cite it using:
S. Karuppayah, L. Böck, T. Grube, S. Manickam, M. Mühlhäuser and M. Fischer, "SensorBuster: On Identifying Sensor Nodes in P2P Botnets" 2017 International Conference on Availability, Reliability and Security, 2017, (In Press).
