# One-Neuron Analysis Using Allen Brain Observatory Dataset

## Introduction  
This project analyzes calcium imaging data of a single neuron recorded in the Allen Brain Observatory Visual Coding dataset.  
The neuron’s activity during drifting gratings stimulus is visualized and analyzed.

## Data & Task  
- Data comes from the Allen Institute for Brain Science.  
- The neuron is from the primary visual cortex (VISp) at 275 µm imaging depth.  
- The goal is to understand neuron responses aligned to stimulus presentations.

## Tools & Libraries  
- Python  
- AllenSDK (for accessing the Allen Brain Observatory data)  
- NumPy  
- pandas  
- matplotlib  

## Project Components  
- Load and filter dataset by brain region, depth, and session type.  
- Extract calcium activity trace (ΔF/F) for one neuron.  
- Plot the full calcium activity trace.  
- Align neuron activity to stimulus start times and plot individual trial responses.  
- Compute and plot the average response with variability shading.  

## Usage  
- Run the Jupyter notebook to reproduce the analysis.   
- The Allen Brain Observatory dataset is stored locally on a disk and accessed directly.

## Results  
Plots saved in the `results/` folder:  
- Full session calcium trace
  <img width="1200" height="400" alt="image" src="https://github.com/user-attachments/assets/456b4f2a-296f-4623-a2d5-284cf291b9f0" />
 
- All trials aligned to stimulus
  <img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/2c300626-0585-4a26-a4f0-c8d67dcb184e" />

- Average response ± standard deviation
  <img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/b9d7bb8a-dfb8-4962-b275-ffcbc31261b7" />


### Results Summary  
The analysis revealed the calcium activity of a single neuron during drifting gratings stimuli.  
- The full calcium trace shows ongoing neuronal activity across the session.  
- Trial-aligned plots display variability in responses to each stimulus presentation.  
- The average response plot highlights a consistent increase in activity shortly after stimulus onset, with variability indicated by standard deviation shading.

These visualizations provide insight into how the neuron responds to visual stimuli over time.

## Future Work  
- Analyze multiple neurons.  
- Explore other stimulus types.  
- Perform further statistical analysis.

## Credits  
Data provided by the Allen Institute for Brain Science.
