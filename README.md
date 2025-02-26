# Li-ion Battery Analysis

This repository contains a collection of notebooks and analyses focused on understanding and predicting the behaviour of Li-ion batteries. The analyses include 3D visualizations of impedance evolution, incremental capacity analysis, and machine learning models for capacity prediction.

---

## 1. **3D Visualization of Battery Impedance Evolution Over Aging**

### Description:
This notebook visualizes the evolution of battery impedance over ageing cycles using a 3D plot. It explores how the real and imaginary parts of impedance change as the battery ages.

### Code:
[`01_Battery_Aging_Impedance_3D_Analysis.ipynb`](https://github.com/johurul000/Li-ion-Battery-Analysis/blob/main/01_Battery_Aging_Impedance_3D_Analysis.ipynb)

### Graph:
![01](https://github.com/user-attachments/assets/23798ff5-d975-4785-9326-4e47605cec05)

---

## 2. **Incremental Capacity Analysis (dQ/dV) for Charge and Discharge Cycles**

### Description:
This notebook performs incremental capacity analysis (dQ/dV) to study the charge and discharge cycles of Li-ion batteries. It calculates and visualizes the dQ/dV curves to identify key battery characteristics.

### Code:
[`02_Incremental_Capacity_Analysis.ipynb`](https://github.com/johurul000/Li-ion-Battery-Analysis/blob/main/02_Incremental_Capacity_Analysis.ipynb)

### Graph:
![02](https://github.com/user-attachments/assets/1fdaf9fb-661f-4a0b-b31b-a7598df7d85f)

---

## 3. **3D Visualization of dQ/dV Peak Evolution Over Battery Aging**

### Description:
This notebook extends the incremental capacity analysis by visualizing the evolution of dQ/dV peaks over battery ageing cycles in a 3D plot. It highlights how the peaks shift as the battery degrades.

### Code:
[`03_3D_Peak_Evolution_Analysis.ipynb`](https://github.com/johurul000/Li-ion-Battery-Analysis/blob/main/03_3D_Peak_Evolution_Analysis.ipynb)

### Graph:
![03](https://github.com/user-attachments/assets/e46fb808-dc4d-420a-88f0-aab773fcc512)

---

## 4. **Battery Capacity Prediction from EIS Data Model**

### Description:
This notebook uses Electrochemical Impedance Spectroscopy (EIS) data to predict battery capacity. It employs a Random Forest Regressor model to predict capacity based on impedance features.

### Code:
[`04_Battery_Capacity_Prediction_From_EIS_Data.ipynb`](https://github.com/johurul000/Li-ion-Battery-Analysis/blob/main/04_Battery_Capacity_Prediction_From_EIS_Data.ipynb)

### Output:
```
Extracted 1956 valid impedance samples.
      Re(Z)     Im(Z)              Capacity
0  0.206678  0.004761    1.7502913788006587
1  0.212963 -0.011729    1.7695250734505363
2  0.214454  0.004741    1.5935866593100128
3  0.216954 -0.010778    0.4668172561120673
4  0.211492  0.004910  0.061130459259873135

Mean Absolute Error (MAE): 0.2774
R² Score: -0.0002
```
