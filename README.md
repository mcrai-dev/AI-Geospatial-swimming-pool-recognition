# AI-based Swimming Pool Detection from Satellite Imagery

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![OpenAI-SAM](https://img.shields.io/badge/AI-SAM%20%2B%20GroundingDINO-red)

## Description
This project automatically detects **swimming pools** in satellite imagery, based on `.kml` geospatial input points.
 It leverages **Grounding DINO** and **Segment Anything** (SAM) to perform semantic segmentation from prompts like `"swimming pool"` or `"blue water"`.

---

## Aperçu visuel

![Output](./screenshot.png) 

---

## Installation

```bash
git clone [https://github.com/mcrai-dev/AI-Geospatial-swimming-pool-recognition.git](https://github.com/mcrai-dev/AI-Geospatial-swimming-pool-recognition.git)
cd AI-Geospatial-swimming-pool-recognition
pip install -r requirements.txt
