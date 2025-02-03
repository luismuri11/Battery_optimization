# Case Studies: Battery Fast-Charging Optimization
In this example, we will explore how to apply an Artificial Neural Network (ANN) to design batteries optimized for fast charging. You will later implement this in Python.

Our objective is to maximize the areal capacity of the battery during fast charging, specifically at 4C rate. To achieve this, we will optimize the porosity of the anode and cathode. We conducted 200 experimental trials to establish the relationship between areal capacity and the porosity of these components.

![Battery optimization](/assets/BatteryCharging)

Areal capacity: Amount of charge a battery can store per unit area of the electrode material, often expressed in mAh/cm².

To facilitate the design process, we will train an ANN with two hidden layers using this experimental data to create a surrogate model. This surrogate model will then be integrated into a gradient-based optimization algorithm to identify the optimal porosity values for both the anode and cathode, thereby maximizing the battery's areal capacity during fast charging.

