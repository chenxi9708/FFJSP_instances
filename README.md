# FFJSP_instances

Detailed data sorce can be found in the paper.

The data format is as follows:

#section 1
jobs machines
operations
the processing time of the first operation of the first jobs

for example:

10 6
6
	 6 12 13	 0 0 0	 7 11 15	 0 0 0	 0 0 0	 0 0 0

10 is number of jobs, 6 is number of machines
6 is number of operation is the first job
6 12 13 are the earliest completion time, the most probable completion time, and the latest completion 

time of the operation O1,1, respectively.


#section 2

"1 0 1 0 0 0" indicate the machines capability for the operation O1,1, where M1 and M3 are able to 

process the opeartion O1,1


#section 3



"0.4 0.3 0.5 0.9 0.5 0.3" indicate the unit energy consumption of machines when processing operations
"0.2 0.2 0.2 0.1 0.1 0.2" indicate the unit energy consumption of machines when standby state
