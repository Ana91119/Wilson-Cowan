# Wilson-Cowan Model: Analyzing Neural Population Dynamics

## Project Overview
This project explores the Wilson-Cowan model, a mathematical framework used to describe the dynamics of neural populations. The model provides insights into the interaction between excitatory and inhibitory neurons under various conditions. 

The analysis includes identifying steady states, assessing stability through Jacobian analysis, modifying non-linear functions, exploring connection strengths, and examining the effects of external stimuli and oscillatory behaviors.

## Repository Contents
- **Wilson_Cowan_Project.ipynb**: Jupyter Notebook containing the implementation, simulations, and visualizations.

## Objectives
The main goal of this project is to analyze the behavior of the Wilson-Cowan model through different tasks:

1. **Finding the Steady States**:
   - Identifying critical points by plotting nullclines (𝑑𝐸/𝑑𝑡 = 0 and 𝑑𝐼/𝑑𝑡 = 0) and estimating their intersections using numerical root-finding techniques.
   - Visualization of steady states where excitatory and inhibitory populations balance.

2. **Classification of Critical Points**:
   - Stability analysis using the Jacobian matrix to determine whether critical points are attractive or repulsive.

3. **Changing Non-Linearities**:
   - Examining the effect of modifying gain parameters (𝑎𝐸, 𝑎𝐼) and thresholds (𝜃𝐸, 𝜃𝐼) on the system’s behavior.
   - Observing how increased sensitivity can lead to instability or adaptability.

4. **Modifying Connection Strength Parameters**:
   - Analyzing the effects of varying inhibitory and excitatory connection strengths (𝑐1, 𝑐2, 𝑐3, 𝑐4) on network stability.
   - Balancing excitatory-inhibitory interactions for biologically realistic dynamics.

5. **External Stimulus Effects**:
   - Investigating how different levels and types of external stimuli (𝑃𝐸(𝑡) and 𝑃𝐼(𝑡)) affect system dynamics.
   - Stability assessment under mild, strong, and unbalanced inputs.

6. **Oscillations**:
   - Studying oscillatory behavior by varying 𝑃𝐸 values.
   - Identifying conditions under which oscillations emerge, stabilize, or disappear.

## Dependencies
To run the Jupyter Notebook, ensure you have the following Python libraries installed:
```bash
pip install numpy matplotlib scipy
