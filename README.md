**Energy_Efficiency**<br>
We are analyzing how different building designs affect energy use, specifically how much heating and cooling a building needs.<br>
You have a dataset of 768 buildings, each with:<br>
&nbsp;&nbsp;&nbsp;8 input features (these describe the building’s structure)<br>
&nbsp;&nbsp;&nbsp;z2 outputs (how much energy the building needs for heating and cooling)<br>
    

    

**Features (inputs):**

&nbsp;&nbsp;&nbsp;1- Relative Compactness – How compact the building is.

&nbsp;&nbsp;&nbsp;2- Surface Area

&nbsp;&nbsp;&nbsp;3- Wall Area

&nbsp;&nbsp;&nbsp;4- Roof Area

&nbsp;&nbsp;&nbsp;5- Overall Height

&nbsp;&nbsp;&nbsp;6- Orientation – The direction the building faces (e.g., north, south) → This is categorical.

&nbsp;&nbsp;&nbsp;7- Glazing Area – How much window area the building has.

&nbsp;&nbsp;&nbsp;8- Glazing Area Distribution – Where the windows are located (e.g., evenly spread, only on one side).

**Targets (outputs):**

&nbsp;&nbsp;&nbsp;1- Heating Load (y1) – How much energy is used for heating?

&nbsp;&nbsp;&nbsp;2- Cooling Load (y2) – How much energy is used for cooling?

**What do we need to do?**

&nbsp;&nbsp;&nbsp;1- Choose one target: either Heating Load or Cooling Load.

&nbsp;&nbsp;&nbsp;2- Predict it using the 8 features above.

&nbsp;&nbsp;&nbsp;3- Use a method called linear regression to build the prediction model.
