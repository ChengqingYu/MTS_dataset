The data set mainly includes 11 commonly used data sets in the field of long series prediction and spatiotemporal prediction. The links to these datasets are given as follows:

Baidu Yun: 
Links: https://pan.baidu.com/s/1Cu1P9twOLHOkIVcKf1BT2Q 
(Passwords: 3bt1)

Google Drive:
Links:https://drive.google.com/file/d/12DvhbUNSOPJnVzSKSnMB0oafvGt63ED2/view?usp=drive_link

These datasets are described as shown below:

1. ETT (Electricity Transformer Temperature) Datasets: ETT is a series of datasets, including ETTh1, ETTm1, ETTh2, and ETTm2, where "1" and "2" represent different transformers. "h" and "m" represent different sampling frequency (every 15 minute and every hour).

2. Electricity: Electricity records the electricity consumption in kWh every 1 hour from 2012 to 2014. It contains 321 clients.

3. Weather: Weather is recorded every 10 minutes for 2020 whole year, which contains 21 meteorological indicators, such as air temperature, humidity, etc. Kindly note that there are multiple versions of Weather dataset in different papers, such as AutoFormer and Informer. We choose the version of AutoFormer.

4. Exchange Rate: The collection of the daily exchange rates of eight countries including Australia, British, Canada, Switzerland, China, Japan, New Zealand, and Singapore.

5. Beijing Air Quality: The air quality index of Beijing, including seven indicators: AQI(Air quality index), PM2.5, PM10, SO2, NO2, O3, and CO. The sampling rate is 1 hours. Missing values are filled using linear interpolation.

6. METR-LA: METR-LA is a traffic speed dataset collected from loop-detectors located on the LA County road network. It contains data of 207 sensors over a period of 4 months from Mar 2012 to Jun 2012. The traffic information is recorded at the rate of every 5 minutes. METR-LA also includes a sensor graph to indicate dependencies between sensors. DCRNN computes the pairwise road network distances between sensors and build the adjacency matrix using a thresholded Gaussian kernel.

7. PEMS-BAY: PEMS-BAY is a traffic speed dataset collected from California Transportation Agencies (CalTrans) Performance Measurement System (PeMS). It contains data of 325 sensors in the Bay Area over a period of 6 months from Jan 2017 to June 2017. The traffic information is recorded at the rate of every 5 minutes. PEMS-BAY also includes a sensor graph to indicate dependencies between sensors. DCRNN computes the pairwise road network distances between sensors and build the adjacency matrix using a thresholded Gaussian kernel.

8. PEMS0X: PEMS0X is a series of traffic flow dataset, including PEMS03, PEMS04, PEMS07, and PEMS08. X represents the code of district where the data is collected. The traffic information is recorded at the rate of every 5 minutes. Similar to METR-LA and PEMS-BAY, PEMS0X also includes a sensor graph to indicate dependencies between sensors.

9. China AQI:  It is a  air quality dataset collected by China Environmental Monitoring Station. And it contains data collected by 350 cities in China from January 2015 to December 2022. For each city, the data is sampled at a 1 hour interval, totaling 59710 time slices.
    
10. ILI: The dataset mainly consists of the major influena-like illness patients in the United States.

11. Traffic: The dataset includes occupation rate of freeway system at 862 measurement points throughout the State of California.








