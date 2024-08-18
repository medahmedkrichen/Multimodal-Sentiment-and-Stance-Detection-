# <div align="center">Multimodal Sentiment and Stance Detection</div>

![Project Banner](https://via.placeholder.com/800x200.png?text=Multimodal+Sentiment+and+Stance+Detection)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction
Welcome to the Multimodal Sentiment and Stance Detection project! This tool is designed to analyze videos and determine the sentiment and stance of individual speakers, as well as the overall tone of the conversation.

## Features
- **Multimodal Analysis**: Combines visual and audio data to provide accurate sentiment and stance detection.
- **Speaker-specific Results**: Analyzes each speaker individually and provides detailed results.
- **Global Analysis**: Provides an overall analysis of the conversation, including host bias if present.

## Installation
To get started with this project, follow the steps below:

1. **Download the Singularity Image**
   - Download the Singularity image from [this link](#) and copy it into the project folder.

2. **Add Videos**
   - Place the videos you want to analyze into the `Videos` folder.

## Usage
To run the analysis, execute the following command in the terminal:

```bash
sbatch template_segmentation.slurm "Gun Control"
```


## Results
After running the analysis, a new file with a name starting with Bias_Results will be created. This file contains the results of the bias analysis for each individual speaker, the global speaker, and the host (if found).

## License
MIT License


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
