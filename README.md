# GPS-X with Python: Simulating Random Events in Wastewater Treatment

## Overview

This repository serves as an informative guide on how to simulate random events affecting a wastewater treatment plant using Python and GPS-X. The tutorial was designed to introduce the concept of randomness in environmental engineering simulations, specifically in the context of wastewater treatment. It aims to provide insights into how unpredictable events like storms can impact the operation of a wastewater treatment plant.

## Objectives

- To demonstrate the use of Python's random number generator for simulating random events in GPS-X.
- To provide a step-by-step guide on setting up a wastewater treatment plant layout in GPS-X.
- To visualize the impact of random events like storms on the treatment plant.
- To implement control mechanisms for managing influent flow rates.
- To introduce the concept of input delays in control mechanisms, simulating real-world scenarios.

## What Was Done

### 1. Setting Up the Layout

A new layout was created in GPS-X, featuring various components essential for a wastewater treatment plant. These components include an influent object, stormwater runoff, a 2-flow combiner, a plug-flow tank, and more. The layout was then saved, and the simulation mode was activated. An output plot was generated to visualize the flow leaving the Influent Combiner.

- A wastewater influent object
- A stormwater runoff (Influent tab)
- A 2-flow combiner
- A plug-flow tank
- A circular secondary clarifier
- A wastewater outfall

![image](https://github.com/engalejandrovargas/Simulating-Random-Events-in-Wastewater-Treatment/assets/77429377/d11be839-800e-4683-b461-60170c308d4a)


### 2. Creating a Random Event

A pre-existing Python script was utilized to introduce random rainfall events into the simulation. The script was edited to customize the random events, including their frequency and severity. Running this script allowed us to visualize how such random events could impact the plant's operation.

### 3. Limiting Maximum Influent

To prevent the plant from being overwhelmed by excessive influent flow, a Control Splitter was added to act as a bypass weir. The Python script was modified to include logic that limits the maximum influent flow to a predefined value. Running this modified script showed how the plant would behave when the influent flow exceeds its maximum capacity.

### 4. Creating an Input Delay

Another Python script was used to introduce a delay in the control mechanism. This was done to simulate the real-world delays that often occur in control loops. The script was edited to implement this delay, and running it showed how such delays could affect the plant's operation.

## Conclusion

This tutorial serves as an educational resource for understanding how Python and GPS-X can be used to simulate and analyze the impact of random events on a wastewater treatment plant. It covers the basics of setting up a layout in GPS-X, introduces randomness through Python scripting, and explores control mechanisms and their limitations.

## License

This project is for educational purposes and is not licensed.
