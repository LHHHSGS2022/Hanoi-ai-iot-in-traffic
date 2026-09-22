# Hanoi-ai-iot-in-traffic
AI &amp; IoT-based Traffic Signal Optimization &amp; Regular Car Benchmark Algorithm for Hanoi Traffic Congestion

# AI & IoT Traffic Optimization System for Hanoi

[![Published Paper](https://img.shields.io/badge/Paper-Published_at_IJMSM_2026-brightgreen?style=flat-square&logo=IEEE)](https://ijmsm.org/ijmsm-v3i3p111.html)
[![DOI](https://img.shields.io/badge/DOI-10.71141%2F30485037%2FV3I3P111-blue?style=flat-square)](https://doi.org/10.71141/30485037/V3I3P111)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)](https://www.python.org/)

This repository contains the simulation code and calibration algorithms for the research paper **"Reducing Traffic Congestion in Hanoi, Vietnam Using Artificial Intelligence and Internet of Things"**, published in the *International Journal of Multidisciplinary on Science and Management (IJMSM)*.

---

## Key Highlights & Contributions

- **Regular Car Benchmark Algorithm:** Developed a calibration method using standard passenger cars as baseline reference points to accurately estimate traffic density and throughput in heterogeneous traffic flows (motorcycles, buses, cars).
- **Edge-AI Video Processing:** Simulated real-time vehicle counting and classification using Computer Vision (YOLO/OpenCV).
- **Adaptive Signal Control:** Evaluated green-wave corridor strategies and reinforcement learning traffic control logic.

---

## Core Performance Metrics

Based on the 2026 implementation data from Hanoi traffic control deployment:
- **Travel Time Reduction:** ~31% – 36.8% on key corridors.
- **Intersection Throughput:** Increased by 13% – 18.88%.

---

## Project Structure

```text
├── data/              # Sample traffic video frames & dataset schema
├── models/            # Vehicle detection & regular-car calibration scripts
├── simulation/        # Traffic flow simulation modules
└── README.md          # Project overview
