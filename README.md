# **Project: Markov Chain Music Generator**

### **Overview**
This project demonstrates how to use **Markov Chains** to generate melodic sequences based on existing musical data. By treating musical notes as 'states' in a stochastic process, we can calculate the probability of transitioning from one note to another.

### **Core Components**
1.  **Data Acquisition**: We use a simplified sequence of notes from Beethoven's *Moonlight Sonata* as training data.
2.  **Model Building**: 
    *   **State Space**: The set of unique notes in the training data.
    *   **Transition Probabilities**: Calculated by counting how often one note follows another in the source material.
3.  **Generation**: Starting from an initial note, the system 'walks' through the Markov Chain, picking the next note based on the learned probability distribution.
4.  **Visualization**: 
    *   **Directed Graph**: Visualizes the flow between notes.
    *   **Heatmap**: Represents the transition matrix for a mathematical overview.
    *   **Melodic Contour**: Compares the shape of the original piece versus the generated output.
5.  **Audio Output**: Converts the generated sequences into MIDI files for playback within the notebook.
