# DMSP_Precipitate_Flux_Prediction
Defense Meteorological Satellite Program (DMSP) Particle Precipitate Flux Prediction (Mesoscale)

🧾**Description:**
We advance the modeling capability of electron particle precipitation from the magnetosphere to the ionosphere through a new database and use of deep learning (DL) tools to gain utility from those data.
We have compiled, curated, analyzed, and made available a new and more capable database of particle precipitation data that includes 51 satellite years of Defense Meteorological Satellite Program (DMSP) observations temporally aligned with solar wind and geomagnetic activity data. 
The new total electron energy flux particle precipitation nowcast model, a neural network called PrecipNet, takes advantage of increased expressive power afforded by ML approaches to appropriately utilize diverse information from the solar wind and geomagnetic activity and, importantly, their time histories. 
With a more capable representation of the organizing parameters and the target electron energy flux observations, PrecipNet achieves a >50% reduction in errors from a current state‐of‐the‐art model oval variation, assessment, tracking, intensity, and online nowcasting (OVATION Prime), better captures the dynamic changes of the auroral flux, and provides evidence that it can capably reconstruct mesoscale phenomena.
We create and apply a new framework for space weather model evaluation that culminates previous guidance from across the solar‐terrestrial research community.

🧭 **Problem Statement:** The target feature is **ELE_TOTAL_ENERGY_FLUX** which is a continuous variable.
The task is to predict this variable based on the other 154 features step-by-step by going through each day's task.
The scoring metric is RMSE or R2 score.
