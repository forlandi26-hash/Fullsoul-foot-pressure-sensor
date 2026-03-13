# Fullsoul-foot-pressure-sensor
This is our repository for the Fullsoul foot pressure sensor project of the winter semester 2025. 
----------------------------------------------------------------------------------------
This project is a further development of the 2024 CACOM project fcosued on wireless plantar pressure measurement using sensor-laden insoles. The intent is to caputre real time pressure data from 208 sensors, to demonstrate shifts in pressure. 
To gain a deeper understanding of what the experiments were like, I suggest reading the fullsoul.pdf, where we go into depth in how we made them. 
To gain a deeper understanding of the code, I suggest reading the Handover protocol, and follow the steeps. 
_quick start_:
1. clone repository git clone:  https://github.com/natalyss16/footsole.git
2. Create & activate conda environment: conda env create -f environment.yml 
(if file exists) or follow the README instructions
3. install missing packages if needed: conda install -c conda-forge pyserial 	h5py matplotlib scipy bleak 	
4. Connect hardware via USB-C → check Device Manager for new COM port
5. Startwired logging (recommended starting point) cd programspython 	log_velostat_sensor_h5.py or python log_velostat_sensor_h5.py 	--log_left
6. Apply pressure to the insole during recording (otherwise data will be empty)
7. check generated .h5 file size (>100-500kb = good) then visualize
-----------------------------------------------------------------------------------------------------------------------------------
**Acknowledgment**
--------------------------------------------------
We gratefully acknowledge **Kai Burain, Chutong Ren, and Arved Strauch** for their foundational work on the Fullsoul project; we also acknowledge the work done by **Tckvitishvili et. al.** for the continuation of this project.
--------------------------------------------------
**Licence**
this repository is provided for educational and research purposes. Reproduction or redistribution must retain full attribution to both the original and current authors. 




**Original repository: https://github.com/weichkai/footPressureSensor**

**previous group:https://github.com/natalyss16/footsole/tree/main?tab=readme-ov-file**
