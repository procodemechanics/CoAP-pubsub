
# Project 
# Evaluation of Application Level IoT Protocols

## **Group members** 

Aman Kumar Gulia: gulia@kth.se 

Patarawan Ongkasuwan: pong@kth.se

Yujue Wang: yujuew@kth.se

Jérôme de Chauveron: jeromedc@kth.se

## **Problem statement**

CoAP takes the advantages of simplicity of UDP but lacks the pub-sub model of MQTT, we want to improve and promote CoAP pubsub model to make it more suitable for real world IoT development.

## **Goals**

1. Carry out an in-depth functional and performance evaluation of MQTT and CoAP running on actual constrained IoT devices.
2. Evaluate CoAP pubsub protocol and compare its performance with MQTT and CoAP.
3. Improve an existing CoAP pubsub broker implementation from KTH to make it more robust suitable for real-world deployment.

## **Design setup**

1. Machine-to-Machine (M2M)
2. Sensor node

## **Evaluation Metrics**

1. RTT(CON-ACK, PUBLISH-PUBACK)
2. Packet overhead - Protocol efficiency(data bytes/(control + data bytes))
3. Packet loss


