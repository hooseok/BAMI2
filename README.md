# BAMI2 PPG dataset

For the experiment, we developed a watch-type PPG measuring device. The developed device includes a 3-channel PPG sensor, an accelerometer and a gyroscope. For the acquisition of the PPG signal, photosensors (SFH 7070, Osram, Germany) integrating two green LEDs(wavelength: 525nm) and a photodetector was used. Three PPG sensors were placed at intervals of 6 mm. Acceleration and gyro values were collected using a 6-axis inertial measurement unit (IMU; LSM6DSMUSTR, STMicroelectronics). Three digital signals were stored using a micro-SD card. The three digital signals are simultaneously stored on a micro-SD card at a frequency of 50 Hz.

The entire exercise process was performed on a treadmill. In the BAMI-II dataset (n=23 ), the exercise protocol included 1 min of rest, 2 min of walking for warm-up at 3–4 km/h, 4 min of running at 6–8 km/h, 4 min of walking at 3–4 km/h, and 1 min of rest to cool down. During every 4-min session of running and walking, the subjects walked or ran while holding a treadmill bar during the last two minutes of the session. We designed the session to reflect cardiac rehabilitation exercise for cardiac patients with poor exercise ability—they normally walk or run by holding a treadmill bar. The subjects comprised 17 males and 6 females with average age of 22.0± 1.7 years. The entire exercise process was also performed on a treadmill. For both datasets, the reference true HRs were measured by ECG data simultaneously recorded by a 24-h Holter monitor (SEER Light, GE Healthcare, Milwaukee, WI, USA). The protocol for data collection and analysis was approved by the Institutional Review Board of Wonkwang University. All participants provided written informed consent.

Citation and copyright 
==================================================
Hooseok Lee, Heewon Chung, and Jinseok Lee (Professor) a member of BAMI LAB.   
https://sites.google.com/site/bamilab/biosignal-lab   

All datasets have copyrights. But you can freely use them for the Signal Processing Cup or your own academic research, as long as you suitably cite the data in your works. Please do not cite this website. Instead, please cite the following paper, since all training datasets come from it: 

Chung, Heewon, et al. "Deep learning for heart rate estimation from reflectance photoplethysmography with acceleration power spectrum and acceleration intensity." IEEE Access 8 (2020): 63390-63402.

URL: https://ieeexplore.ieee.org/document/9042276

Exercise Experiment Protocol
==================================================
Measurements were taken using an ECG placed on the chest together with a PPG placed on the wrist during treadmill exercise. ECG data were recorded simultaneously using a 24-hour Holter monitor (SEER Light; GE Healthcare, Milwaukee, WI, USA). PPG and motion data were recorded using a wearable device which we developed. Participants were asked to perform the exercise according to the exercise protocol, we have designed. 
  1) Stay (Resting)         : 1minutes
  2) Walking                : 2minutes, treadmill (3-4 km/h)
  3) Running                : 2minutes, treadmill (6-8 km/h)
  4) Running (grab the bar) : 2minutes, treadmill (6-8 km/h)
  5) Walking                : 2minutes, treadmill (3-4 km/h)
  6) Walking (grab the bar) : 2minutes, treadmill (3-4 km/h)
  7) Stay (Resting)         : 1minutes


Data Description
==================================================
This database contains wrist PPGs recorded during stay, walking, and running.
Accelerometers and Gyroscopes are collected to remove the motion artifact from the PPGs.
A reference chest ECG is included to allow a gold-standard comparison of heart rate during treadmill exercise.

●ECG sampling rate : 125Hz   
●PPG sampling rate : 50Hz  
●Acc sampling rate : 50Hz  
●Gyro sampling rate : 50Hz   

Matlab Data
==================================================
●bpmECG    : ECG heart rate   
●timeECG   : ECG times  
●sigPPG    : 3-channel PPG signal   
●sigAcc    : 3-axis accelerometer signal, An uncorrected digital value, with a value of 32768 added to remove the negative number.   
●sigGyro   : 3-axis gyroscope signal,  An uncorrected digital value, with a value of 32768 added to remove the negative number.    
