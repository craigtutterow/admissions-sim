admissions-sim
------

Simulation/formulas for calculating the acceptance and matriculation rates of schools in a system with a constant number of schools and students, but an increasing number of applications per student.

It is straightforward to show that acceptance rates decrease as a function of the number of applications per student. This simulation and the accompanying formulas show that average yield rates (for schools) also decline as a function of the number of applications per student. 

We argue that the increasing number of applications per student is part of a feedback cycle. Lower acceptance rates lead to more uncertainty for students about admission, leading them to apply to more schools. This leads to further reductions in acceptance rates, which reinforces more of the same behavior. Increasing the number of applications per student also increases the probability that students will receive a competing offer, therefore decreasing the probability that any accepted student will enroll. This dynamic leads to greater competition for both students and schools, leading them to seek third party consultants to mitigate uncertainty about acceptance and enrollment.

###admissions_simulation.ipynb:
Jupyter notebook reproducing results from the paper, including validation of simulation results and derived formulas.

###admissions_simulation.py:
Raw python code as exported from Jupyter notebook.

###admissions_simulation.html:
HTML output as exported from Jupyter notebook. 

----
**As described in**: [Craig Tutterow , James A. Evans (2016), Reconciling the Small Effect of Rankings on University Performance with the Transformational Cost of Conformity, in Elizabeth Popp Berman , Catherine Paradeise (ed.) The University Under Pressure (Research in the Sociology of Organizations, Volume 46) Emerald Group Publishing Limited, pp.265 - 301](https://www.researchgate.net/publication/298638826_Reconciling_the_small_effect_of_rankings_on_university_performance_with_the_transformational_cost_of_conformity)
