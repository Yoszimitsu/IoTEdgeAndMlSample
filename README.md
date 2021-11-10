---
page_type: sample
languages:
- csharp
- python
- powershell
products:
- azure-iot-hub
- azure-iot-edge
- azure-machine-learning-service
name: Machine Learning and IoT Edge
urlFragment: MLandIotEdge
description: "Training a machine learning model in the cloud with data collected from IoT devices, and deploy the model to IoT Edge."
---
# Machine Learning and IoT Edge

Frequently, IoT applications want to take advantage of the intelligent cloud and the intelligent edge. In this sample, we walk you through training a machine learning model with data collected from IoT devices in the cloud, deploying that model to IoT Edge, and maintaining and refining the model periodically.

## Instructions for completing the walk-through

The detailed walk-through instructions for this sample can be found at <https://docs.microsoft.com/en-us/azure/iot-edge/tutorial-machine-learning-edge-01-intro>.

## Feedback

If you have problems with this sample, please post an issue in this repository.

## Notes

- Sku "rs5-pro" is not availbale anymore. I was change to "21h1-pro" Windows version.
- It's necessary to check Quota for Azure region, becasue "Standard_D8s_v3" had to much cores (8) for that region and exceeded the limit. I've changed on "Standard_A2m_v2" VM.
