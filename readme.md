
  # Reorganisation of cortical inter-areal network during learning of a sensorimotor transformation behaviour 📝  
  Welcome to my computational neurosciences minor project code - which is called **ReconSTB** for brevity! I had the chance to work on sensorimotor spiking data in [the Laboratory of 
  Sensory Processing](https://www.epfl.ch/labs/lsens/) at [EPFL](https://www.epfl.ch/en/). The goal of this project was to explore trial-by-trial variability and correlation between sensorimotor neuron populations. The following repo contains the final jupyter notebook along with some generated figures. 
  
  ## Requirements 🚀  
  Please make sure you have the following libraries installed, along with ipykernel to run the notebook :
  - python >= 3.9.1
  - scipy >= 1.6.0
  - matplotlib >= 3.3.3
  - numpy >= 1.19.5
  - mat73 >= 0.46

  ## Data
 Please note that the lab's data used in this project is not included in this repository. The code provided here is intended for demonstration and educational purposes. To reproduce the results or run the code, you will need to obtain the necessary data from the lab's source.

If you have access to the lab's data, you can place it in the appropriate directory and update the file paths in the code accordingly.

Here, I am using `data_wS1_wM1_wS2_wM2_Exp.mat` which is a MATLAB© structure containing mainly spiking data along with other metadata. The keys of this dict are printed in the notebook under the first section.
  
  ## License

The MIT License (MIT)
Copyright (c) 2021 Jan Mikolaj Waligorski

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
