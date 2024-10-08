# <div align="center">Multimodal Sentiment and Stance Detection</div>


<div align="center">
  <table  border="0">
    <tr>
      <td>
  <p>
    <a href="https://www.redhenlab.org" target="_blank">
      <img width="300px" height="300px" src="Images/redhenlabimage.png"></a>
  </p>
    </td>  
<td>
<p>
    <a href="https://summerofcode.withgoogle.com" target="_blank">
      <img width="500px" height="300px" src="Images/gsoc11.jpg"></a>
  </p>
      </tr>
        </td>
</table>
</div>



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
   - Download the Singularity image from [this link](https://esprittncom-my.sharepoint.com/:u:/g/personal/mohamedahmed_krichen_esprit_tn/EV8QCCMLL9FDtdjrsMU76vYBrH5T_0uOJ89d3BMHf_5u3w?e=MXnEVa) and copy it into the project folder.

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

