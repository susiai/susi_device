# SUSI Device

This project contains the sources to install SUSI elements on a Raspberry Pi.
For now we try to combine the following elements:

- a microphone and a speaker
- a small display
- a local LLM (large language model)
- a docker environment to host docker containers

We try to provide SUSI application parts as docker images. This should help to deploy the SUSI ecosystem also on non-Raspberry Pi devices to enhance the ability for developers to join in even if they don't have a SUSI device. However, it is the target to run everything in place using only open source elements and without any internet connection offline.
