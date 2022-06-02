Coding Language used: Python 3.8.6
IDLE : Jupyter note book

Necessary dependencies for running files:
1. matplotlib
2. numpy
3. math
4. Jovian ( this is something like git for github, can ignore )
5. mcolors for different colors for gantt chart plotting.

In the case where the dependencies are not installed, run this command:
	py -m pip install <package_name>

##################################
Coding Script:
##################################

1)EDRR_differencearrivial.ipynb
2)EDRR_samearrival.ipynb
3)IDRR_differencearrivial.ipynb
4)IDRR_samearrival.ipynb
5)EDRR IDRR BINOMIAL TASK Generator.ipynb

##################################
How to run?
##################################
1) Open the script
2) import the necessary libaray required in the first cell
3) You can run jupyter per cell using (Shift + enter)

Task generator is incorporated in each file
4) Next, it will prompt the user if they want manual or auto mode for task generating
5) Choose M or m for manual 
6) Choose A or a for auto

7) For manual mode, it will ask if it is a same arrival or different arrival
8) Set the number of process you want
9) key in only the burst time for same arrival
10) Key in burst time and arrivla time for different arrival
11) At the end, it will save into a excel file, for example EDRR_Samearrival.xlsx

12) For auto mode, each script will ask how many process you need and generate automatically
13) In order to change the gaussian parameters, just set the desired parameters you want and run the cell again

14) NOTE THAT the author has changed the name to for the generated excel file to the names as shown below
15) Set the desired file name and run the cell for each script

dataFrame = pd.read_excel('filename you want')


You may contact me at +65 91099666 or email me at e0191455@u.nus.edu if you faced any difficulty running.

##################################
Generated task sets (Different Arrival): 
###################################

1) Gaussian Distribution for 

Arrival Time Mean: 10 , Sigma : 5 
Burst Time Mean: 50 , Sigma : 20

Simulation_diffarrival_30_at_10_5_bt_50_20.xlsx
Simulation_diffarrival_150_at_10_5_bt_50_20.xlsx
Simulation_diffarrival_350_at_10_5_bt_50_20.xlsx
Simulation_diffarrival_550_at_10_5_bt_50_20.xlsx
Simulation_diffarrival_850_at_10_5_bt_50_20.xlsx
Simulation_diffarrival_1000_at_10_5_bt_50_20.xlsx

2) Gaussian Distribution for 
Arrival Time Mean: 10 , Sigma : 5 
Burst Time Mean: 50 , Sigma : 35

Simulation_diffarrival_30_at_10_5_bt_50_35.xlsx
Simulation_diffarrival_150_at_10_5_bt_50_35.xlsx
Simulation_diffarrival_350_at_10_5_bt_50_35.xlsx
Simulation_diffarrival_550_at_10_5_bt_50_35.xlsx
Simulation_diffarrival_850_at_10_5_bt_50_35.xlsx
Simulation_diffarrival_1000_at_10_5_bt_50_35.xlsx
Simulation_diffarrival_30_at_10_5_bt_50_35.xlsx

3) Gaussian Distribution for 
Arrival Time Mean: 10 , Sigma : 10 
Burst Time Mean: 50 , Sigma : 20

Simulation_diffarrival_30_at_10_10_bt_50_20.xlsx
Simulation_diffarrival_150_at_10_10_bt_50_20.xlsx
Simulation_diffarrival_350_at_10_10_bt_50_20.xlsx
Simulation_diffarrival_550_at_10_10_bt_50_20.xlsx
Simulation_diffarrival_850_at_10_10_bt_50_20.xlsx
Simulation_diffarrival_1000_at_10_10_bt_50_20.xlsx

4) Binomial Distribution for 
Arrival Time n: 15 , p : 0.5 
Burst Time Mean: n: 100 , p: 0.4

Binomal_850_different_arrival15_0.5burst100_0.4.xlsx
Binomal_1000_different_arrival15_0.5burst100_0.4.xlsx
Binomal_1500_different_arrival15_0.5burst100_0.4.xlsx
Binomal_2000_different_arrival15_0.5burst100_0.4.xlsx



########################
Generated task sets (Same Arrival): 
########################

5) Gaussian Distribution for 

Burst Time Mean: 50 , Sigma : 20

Simulation_samearrival_30_bt_50,20.xlsx
Simulation_samearrival_150_bt_50,20.xlsx
Simulation_samearrival_350_bt_50,20.xlsx
Simulation_samearrival_550_bt_50,20.xlsx
Simulation_samearrival_850_bt_50,20.xlsx
Simulation_samearrival_1000_bt_50,20.xlsx

6) Gaussian Distribution for 

Burst Time Mean: 50 , Sigma : 35

Simulation_samearrival_30_bt_50,35.xlsx
Simulation_samearrival_150_bt_50,35.xlsx
Simulation_samearrival_350_bt_50,35.xlsx
Simulation_samearrival_550_bt_50,35.xlsx
Simulation_samearrival_850_bt_50,35.xlsx
Simulation_samearrival_1000_bt_50,35.xlsx


