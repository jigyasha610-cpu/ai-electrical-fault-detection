# AI-Based Electrical Fault Detection System

AI & GenAI Hands-on Project (Edunet Foundation)

**Student:** Jigyasha Kumari
**Institution:** Government Polytechnic Jajpur, Electrical Engineering
**Registration no.:** F25126002022

## Problem
Overloads, short circuits and abnormal currents damage equipment and create fire and shock hazards. Fuses and simple relays react only after a fixed limit is crossed and cannot tell fault types apart.

## Solution
A Random Forest classifier that reads current and voltage windows, detects a fault and classifies it as **Normal, Overload, Short-circuit or Abnormal current**, then raises an alert and trips a relay.

## Features used
RMS, peak, crest factor, THD, di/dt, phase imbalance, voltage RMS.

## Working model
Open `index.html` (or the GitHub Pages link) for the interactive dashboard: live waveforms, feature values, class probabilities, LEDs, buzzer, relay trip/reset, accuracy and confusion matrix.

Note: the data in this demo is simulated in software. Hardware protection (fuse / breaker) stays in place; the AI layer detects, classifies and alerts.

## Tech
Python (scikit-learn, XGBoost, TensorFlow Lite), ESP32 / Raspberry Pi, CT / ACS712, ZMPT101B, MQTT, Grafana. The web demo is plain HTML and JavaScript.
