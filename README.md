<p align="center">
  <img src="assets/header.svg" alt="ikoTrain — Embedded experiments. Measured results." width="100%">
</p>

I work on embedded experiments that connect **physical measurements, firmware, and data**. Currently building **ProduceSense** on the ESP32-S3.

### Featured project · ProduceSense

**Can two electrodes tell an apple from a potato?**

An ESP32-S3 prototype that classifies apples, potatoes, and cucumbers using a **10 kΩ resistor**, two electrodes, and six transient-voltage features. Inference runs on the microcontroller.

| Hardware | Recorded evaluation | Response time |
|:---|:---|:---|
| ESP32-S3 · 2 electrodes · 1 resistor | 30/30 placements on 15 specimens | 7.6 seconds |

The result describes one recorded evaluation series, with two placements per specimen.

[**Explore the project →**](https://github.com/ikoTrain/ProduceSense) · [Read the experiment](https://github.com/ikoTrain/ProduceSense/blob/main/docs/article.md) · [PDF](https://github.com/ikoTrain/ProduceSense/blob/main/docs/ProduceSense-English.pdf)

<p align="center">
  <a href="https://github.com/ikoTrain/ProduceSense">
    <img src="https://raw.githubusercontent.com/ikoTrain/ProduceSense/main/docs/assets/scatter.png" alt="Forward and reverse pulse voltages from 30 electrode placements across 15 specimens" width="760">
  </a>
</p>

### What I’m exploring

- **Hardware:** electrode interfaces, ADC readings, and transient responses.
- **Firmware:** timed acquisition and on-device classification with Arduino/C++.
- **Experiments:** controls, repeat measurements, and reproducible analysis.

### Inside my projects

Wiring diagrams, source code, measurement records, and explanations of the design decisions.
