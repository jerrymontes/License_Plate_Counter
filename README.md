# The Car that Keeps Driving by my House: License Plate Counter
Capstone Project By: Jerry Montes


# Problem Statement
I will train a neural network to detect license plates in video footage and count the frequency with which unique license plates are detected.

# Datasets
## License Plate Detection Datasets:
- https://github.com/winter2897/Real-time-Auto-License-Plate-Recognition-with-Jetson-Nano/blob/main/doc/dataset.md
- https://ieee-dataport.org/open-access/cd-lp-compressed-domain-license-plate-detection-database#files
## Digit/Character Detection Datasets: 
- https://github.com/winter2897/Real-time-Auto-License-Plate-Recognition-with-Jetson-Nano/blob/main/doc/dataset.md
- https://search.datacite.org/works/10.6084/m9.figshare.3113449

# Approach
Training two neural nets (one for detecting license plates and another for detection and classification of digits/characters)

# Objectives
To combine both neural networks and create an algorithm capable of detecting license plates and the digits/characters on them and thereafter record the number.

# Goal
To add this algorithm to a camera such that, when exposed to cars, it detects their license plates and records that information

# Success Metric
- For neural network that detects license plate: Precision
- For neural network that detects digits/characters: Accuracy

# Risks
Dataset is foreign and not easily applicable to American license plates (1-row)

# Assumptions
Camera this algorithm is eventually added to will have sufficient resolution to both detect license plates and the digits/characters on them
