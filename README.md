# OPPCL
1. OPPCL tests two datasets (SWaT and ETT), and the code is stored in the corresponding folders.
2. The data folder contains the raw dataset data, the processing code for both datasets, and the processed data.
3. Pattern_exchange.py in the SWaT folder is the entire OPPCL program and can be run directly. The length_pattern and window_size must be the same. BaseModel.py does not use CL; adjust the window_size as needed and run directly. The same applies to the ETT folder.
4. The corresponding "Comparative Experiments" subfolders in both folders contain all the comparative experimental models mentioned in the paper. Adjust the window_size as needed and run directly.
5. Core environment dependencies:
1) numpy = 1.24.4
2) pandas = 1.5.3
3) torch = 2.4.1 (GPU)
4) python = 3.8.19
5) GPU = NVIDIA GeForce RTX 4070
6) CUDA Version = 12.3
6. After the core dependencies are met (except for the GPU and CUDA versions, which can be adjusted), if any dependencies are missing during runtime, you can directly pip install xxx to resolve them.
