# dad
DATASET for Anomaly Detection in IoT Networks

DAD is a semi-synthetic and labeled dataset consisting of seven days network activity with attacks spread over five days. It has three  different types of anomalies: duplication, interception and modification on the MQTT message. 

The anomaly traffic is made from IP source 10.6.56.41. The attacks has been done in specific days of the week. 
The distribution is as follows:

- Monday 21st: there is no attacks.
- Tuesday 22nd: some packets have been removed, so packets are not labeled as attack.
- Wednesday 23rd: a modification of packets is made between 4h and 6h.
- Thursday 24th: insertion of packets in less than 5 minutes at 3h. 
- Friday 25th: a mix of interception, duplication and modification is done at 6h and between the 14-16h.
- Saturday 26th: a mix of interception, duplication and modification is done at 6h and between the 14-16h.
- Sunday 27th: there is no attacks.

Information & Citation Request:

L. Vigoya, D. Fernandez, V. Carneiro and F. Cacheda, Annotated Dataset for Anomaly Detection in a Data Center with IoT Sensors, Sensors 2020,20,3745;doi:10.3390/s20133745
