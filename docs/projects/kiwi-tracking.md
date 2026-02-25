---
sidebar_position: 1
title: Kiwibot Tracking
---

# Kiwibot Tracking

We are atempting to build a network of devices placed around the UWEC campus that records the position of the Kiwibot robots using wireless signal triangulation (Bluetooth or Wi-Fi). The goal is to prove that the Kiwibots are driving around campus aimlessly and are not significantly contributing positively to campus.

Source Code: https://github.com/Blugold-Group/TriangulationNet

## Hardware:

We have not completely solidified what hardware we are using. However, the ideal plan would be to use ESP32 devices. Due to the codebase being written in Python, the current working idea is Raspberry Pi devices as it is not as feasable to use ESP32s and would require a significant amount of work to port over. 

## Placement:

The logical idea—once the specific device is figured out—would be to place devices around campus covering walkways where Kiwibots travel. This way we can triangulate the position of the bots and track their movements.
