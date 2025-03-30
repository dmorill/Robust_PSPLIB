Robust PSPLIB<br />

This is the new library of instances for the Resource-Constraint Project Scheduling Problem (RCPSP) under stochastic processing time of activities. This library is based on the classical PSPLIB [1] (https://www.om-db.wi.tum.de/psplib/main.html) and consist of four sets of instances of 30, 60, 90, 120 jobs; all with 480 instances except the last set which has 600. To include the new features, this library was made by a realistic risk methodology, thus some jobs have been chosen that have one or two risks, each one affects the duration of the job following a normal distribution function. All details can be found in [2].<br />

[1] Kolisch, R. and Sprecher, A. (1997) 'PSPLIB - A Project Scheduling Problem Library', European Journal of Operational Research, 96(1), pp. 205-216. https://doi.org/10.1016/S0377-2217(96)00170-1. <br />
[2] Working paper. <br />

Regarding the format, the new instances include all stochastic information in the last part of the file by following the next format:<br />

Job	#risk	Type	VL	mu	sigma	Type	VL	mu	sigma <br />

Where:<br />
Job = number of the job. <br />
#risk = number of risks that the job has (can be 1, 2). <br />
Type = type of risk from the eight possibilities. <br />
VL = variability level of the risk. <br />
Mu = mean of normal distribution. <br />
Sigma = standard deviation of the normal distribution. <br />

--<br />
Hidden for review <br />
Ph.D. Student<br />
Affiliation<br />
mail@mail.com <br />
