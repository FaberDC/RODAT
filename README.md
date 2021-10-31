# RODAT
Resilience-oriented Decision mAking Tools in Power System (Review Insights)


|Title                                                                                                                                 |Year|1st Author                |DOI                        |Included in the review|Resilience Stage                            |Paper Target                                                                                                |Grid Level  |Case Study                                                   |Scenario Generation Strategy                                                                                                                                                                                                                                                                                                                                                                                                                            |Analyzed Time Steps|Starting Number of Scenarios|Final Number of Scenarios|Resilience Against|Considered Uncertainty Variables                                                       |Type of Study                                                                                                                                                                                                                                                   |Proposed Model Name                                            |Computational Time (s)|Power Flow|Notes                                                                                                                                                                                                         |
|--------------------------------------------------------------------------------------------------------------------------------------|----|--------------------------|---------------------------|----------------------|--------------------------------------------|------------------------------------------------------------------------------------------------------------|------------|-------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|----------------------------|-------------------------|------------------|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|----------------------|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Power Grid Resilience Enhancement via Protecting Electrical Substations Against Flood  Hazards: A Stochastic Framework                |2022|Mohadese Movahednia       |10.1109/TII.2021.3100079   |Y                     |Pre-event (Resilience-oriented operation)   |Risk Aware Stochastic Scheduling                                                                            |Distribution|30-bus system                                                |flood pdf montecarlo generation                                                                                                                                                                                                                                                                                                                                                                                                                         |10                 |Very Large                  |17                       |Flood             |flood height                                                                           |Unit Commitment by considering two sets of different uncertainty sources: Normal (Load & wind power forecasting error, electricity prices) - Resilience (Islanding Duration).                                                                                   |-                                                              |-                     |DC        |-                                                                                                                                                                                                             |
|Leveraging Network Topology Optimization to Strengthen Power Grid Resilience Against Cyber-Physical Attacks                           |2021|Zhaoxi Liu                |10.1109/TSG.2020.3028123   |Y                     |Pre-event (Resilience-oriented operation)   |Optimal Redispatch considering Bus switching                                                                |Transmission|modified IEEE 57-bus, IEEE 118-bus                           |The first level of the problem select the  set of cyberattack maximizing the load shedding given a maximum number of action                                                                                                                                                                                                                                                                                                                             |?                  |Very Large                  |1                        |Cyber-Attacks     |Bus, Lines, Generation Units                                                           |The algorithm find the best network topology minimizing the load shedding when                                                                                                                                                                                  |Network Topology Optimization                                  |-                     |AC        |Bi-level problem (one maximize the grid damage)                                                                                                                                                               |
|Power System Resilience Enhancement in Typhoons Using a Three-Stage Day ahead Unit Commitment                                         |2021|Tao Ding                  |10.1109/TSG.2020.3048234   |Y                     |Pre-event (Resilience-oriented operation)   |Security Unit Commitment                                                                                    |Transmission|IEEE 118-bus system, Chinese provincial grid                 |Estimated typhoon spatial trajectory, all lines located in typhoon path are considered outaged                                                                                                                                                                                                                                                                                                                                                          |24                 |Very Large                  |?                        |Typhoon           |Lines                                                                                  |Three-level Unit Commitment                                                                                                                                                                                                                                     |Three-level Unit Commitment                                    |1800                  |DC        |It considers all the resilience stages: preventive, operative, and restorative                                                                                                                                |
|Resilience-Promoting Proactive Hurricanes in Multiple Energy Carrier Microgrids Scheduling Against                                    |2021|Mohammad Hassan Amirioun  |10.1109/TPWRS.2018.2881954 |Y                     |Pre-event (Resilience-oriented operation)   |MC and Electric / Gas Storage are scheduled to enhance the preparedness of the grid to a predicted Hurricane|Distribution|modified IEEE 33-bus                                         |Unit Commitment by considering Multiple Energy Carrier Microgrids (Electric and Gas). The path and hits of hurricanes are known.                                                                                                                                                                                                                                                                                                                        |12                 |-                           |-                        |Hurricanes        |None                                                                                   |A Unit Commitment with MC is performed to enhance the preparedness of the system to face with a Hurricane                                                                                                                                                       |.                                                              |20                    |AC        |-                                                                                                                                                                                                             |
|Resilient Unit Commitment for Day-Ahead Market Considering Probabilistic Impacts of Hurricanes                                        |2021|Tianyang Zhao             |10.1109/TPWRS.2020.3025185 |Y                     |Pre-event (Resilience-oriented operation)   |Resilient Unit Commitment                                                                                   |Transmission|IEEE Reliability Test System and IEEE RTS-96                 |The Distributionally robust optimization requires the building of the ambiguity set. 1000 scenarios are built considering the uncertainty variables. Line failure probabilities consider several stress variables as wind speed and rainfall level. The probability over the time are computed according to a continuous Markov process. A line is considerable prones to be failure if its corresponding probability is greater than a given threshold.|24                 |-                           |-                        |Hurricanes        |Hurricane track, translation speed, center of pressure, line status, load power profile|A Robust Unit Commitment and a Distributionally Robust Commitment are jointly solved.                                                                                                                                                                           |-                                                              |-                     |DC        |                                                                                                                                                                                                              |
|Risk-Based Stochastic Scheduling of Resilient Microgrids Considering Demand Response Programs                                         |2021|Mostafa Vahedipour-Dahraie|10.1109/JSYST.2020.3026142 |Y                     |Pre-event (Resilience-oriented operation)   |Risk-based Optimal Scheduling of MG                                                                         |Distribution|single bus power system model                                |Unit Commitment by considering two sets of different uncertainty sources: Normal (Load & wind power forecasting error, electricity prices) - Resilience (Islanding Duration). The number of scenarios is generated by Monte-Carlo Simulation, and they are reduced by k-means algorithm                                                                                                                                                                 |24                 |2000                        |27                       |-                 |Load Demand and Renewable Generation, Price, Islanding duration                        |Unit Commitment by considering two sets of different uncertainty sources: Normal (Load & wind power forecasting error, electricity prices) - Resilience (Islanding Duration).                                                                                   |-                                                              |-                     |-         |-                                                                                                                                                                                                             |
|Distributionally Robust Distribution Network Configuration Under Random Contingency                                                   |2020|Sadra Babaei              |10.1109/TPWRS.2020.2973596 |Y                     |Pre-event (Resilience-oriented operation)   |Unit Commitment in the post contingency restoration                                                         |Distribution|IEEE 33-bus distribution system, 69 node grid, 123 node grid |The Bernoulli Distribution is considered to model each line contingency probability                                                                                                                                                                                                                                                                                                                                                                     |24                 |Ver Large                   |1                        |-                 |Lines                                                                                  |Two stages Distributional Robust Optimization                                                                                                                                                                                                                   |-                                                              |-                     |AC        |-                                                                                                                                                                                                             |
|Identifying Optimal Portfolios of Resilient Network Investments Against Natural Hazards, With Applications to Earthquakes             |2020|Tomas Lagos               |10.1109/TPWRS.2019.2945316 |Y                     |Pre-event (Resilience-oriented planning)    |Identification of the best hardening strategies to enhance the grid resilience against earthquakes          |Transmission|modified IEEE 14-bus grid                                    |Set of Scenarios built by considering Monte-Carlo Generation according to Gutemberg-Ritcher exponential distribution (for the earthquake magnitude) and uniform distribution over a square 500x500 km^2 (for the earthquake location)                                                                                                                                                                                                                   |24                 |Very Large                  |10000                    |Earthquakes       |Substation, Towers, Generations units                                                  |Optimized via Sampling (Three-stages-based: 1) global search engine for best                                                                                                                                                                                    |Industrial Strength COMPASS                                    |(Very Intensive)      |DC        |-                                                                                                                                                                                                             |
|Markov Decision Process-Based Resilience Enhancement for Distribution Systems: An Approximate Dynamic Programming Approach            |2020|Chong Wang                |10.1109/TSG.2019.2956740   |Y                     |During-event (Resilience-oriented operation)|Dispatching System Topology                                                                                 |Distribution|IEEE 33-bus system, IEEE 123-bus system                      |The grid topology is modeled as a Markov chain where the uncertainty represents the failure probability considering the trajectory of the hurricanes over the time.                                                                                                                                                                                                                                                                                     |6                  |Very Large                  |1                        |Hurricanes        |Lines                                                                                  |Optimal Dispatching Topology. The stochastic problem is transformed in a deterministic one by proposing a Markov Decision Process. The curse of dimensionality is addressed through   Post Decision State and Approximate Dynamic Programming                   |-                                                              |High (offline)        |AC        |-                                                                                                                                                                                                             |
|Multidimensional Scenario Selection for Power Systems With Stochastic Failures                                                        |2020|Farshad Mohammadi         |10.1109/TPWRS.2020.2990877 |Y                     |Pre-event (Resilience-oriented operation)   |Scenario Reduction                                                                                          |Transmission|2000 bus Texas synthetic grid                                |Estimated spatial trajectory of hurricane, radial wind speed profile distribution, a map is built to consider fault probability and LODF-base network impact. The component more at right and upper the considered threshold will be considered down for all time steps.                                                                                                                                                                                |24                 |Very Large                  |Until 17                 |Hurricanes        |Lines                                                                                  |Two-state Stochastic Unit Commitment                                                                                                                                                                                                                            |Multidimensional Scenario Selection                            |72360                 |DC        |-                                                                                                                                                                                                             |
|Resilience Constrained Day-Ahead Unit Commitment Under Extreme Weather Events                                                         |2020|Dimitris N. Trakas        |10.1109/TPWRS.2019.2945107 |Y                     |Pre-event (Resilience-oriented operation)   |Security Unit Commitment                                                                                    |Transmission|IEEE 118-bus system, IEEE-Reliability Test System            |Wind Speed Profile for the same area, worst case scenarios are built by considering a failure probability threshold. each scenario is multi-temporal path of the state grid over the time. The second level of the optimization problem identifies the line failures that lead to the highest operational costs                                                                                                                                         |24                 |-                           |-                        |Windstorm         |Lines and towers per km                                                                |Two-stage Robust Unit Commitment                                                                                                                                                                                                                                |Column and Constrained Unit Commitment                         |3155                  |DC        |C.T is referred to IEEE-118 bus system                                                                                                                                                                        |
|Enhancing Resilience Level of Power Distribution Systems Using Proactive Operational Actions                                          |2019|Babak Taheri              |10.1109/ACCESS.2019.2941593|Y                     |Pre-event (Resilience-oriented operation)   |Stochastic Optimization                                                                                     |Distribution|47-bus real grid                                             |Set of Scenarios simulated by Monte-Carlo Simulation and Reduced via SCENRED toolbox (GAMS)                                                                                                                                                                                                                                                                                                                                                             |24                 |1000                        |10                       |-                 |Lines                                                                                  |stochastic Optimization                                                                                                                                                                                                                                         |-                                                              |-                     |AC        |It consider crew time in the model                                                                                                                                                                            |
|Transmission System Resilience Enhancement with Extended Steady-state Security Region in$2 Consideration of Uncertain Topology Changes|2019|Chong Wang                |correarXiv: 1911.09987v1   |Y                     |Pre-event (Resilience-oriented operation)   |Security Unit Commitment                                                                                    |Transmission|IEEE 118-bus system                                          |Monte-Carlo generation by considering the most probable trajectories considering the hurricane path                                                                                                                                                                                                                                                                                                                                                     |24                 |Very Large                  |Until 1400               |Hurricanes        |Lines                                                                                  |Bilevel Optimization                                                                                                                                                                                                                                            |Extended steady-state security  region                         |-                     |DC        |-                                                                                                                                                                                                             |
|Resilience Constrained hourly unit commitment in electricity grids                                                                    |2018|Yifei Wang                |10.1109/TPWRS.2018.2817929 |Y                     |Pre-event (Resilience-oriented operation)   |Three-level Security Unit Commitment                                                                        |Transmission|IEEE 30-bus system                                           |The line failure probability is modeled through a Proportional Hazard Model, which considers wind speed and power flow load rate at t and line x. The line is considered outaged when a sample value is greater than the corresponding cumulative failure probability.                                                                                                                                                                                  |24                 |Dynamic                     |200                      |Typhoon           |Lines                                                                                  |A sequential and Monte-Carlo based unit-commitment is performed. Sequential means for each time step a outage sampling is performed. Monte-Carlo-based means the optimization is repetead until a convergence criteria with the Monte-Carlo results is obtained.|Resilience-Constrained Unit Commitment                         |-                     |DC        |It considers the power flow entropy to lead to a homogeneous power flow on the lines, it model fault considering line rate usage and weather condition, the probability of failure is cumulative over the time|
|Resilience-Oriented Proactive Management of Microgrids Against Windstorms                                                             |2018|M. H. Amirioun            |10.1109/TPWRS.2017.2765600 |Y                     |Pre-event (Resilience-oriented operation)   |Unit Commitment                                                                                             |Distribution|IEEE 33-bus distribution system                              |Estimated spatial wind speed, all elements having a failure probability greater than a certain threshold are considerable vulnerable. The algorithm iteratively run a AC-OPF to find the grid topology having the least number of vulnerable component minimizing the VOLL                                                                                                                                                                              |24                 |Very Large                  |1                        |Windstorm         |Lines, Poles                                                                           |One stage Unit Commitment                                                                                                                                                                                                                                       |One stage Unit Commitment (but it is decomposed in three stage)|-                     |AC        |It considers the role of microgrids in enhancing the resilience                                                                                                                                               |
|Quantitative Resilience Assessment under a Tri-Stage Framework for Power Systems                                                      |2018|Han Zhang                 |10.3390/en11061427         |Y                     |During-event (Resilience-oriented operation)|DC-OPF to minimize Loss of Load                                                                             |Transmission|IEEE RTS 79                                                  |-                                                                                                                                                                                                                                                                                                                                                                                                                                                       |24                 |-                           |-                        |-                 |lines                                                                                  |Deterministic Optimization                                                                                                                                                                                                                                      |-                                                              |-                     |AC        |-                                                                                                                                                                                                             |
|Resilience Enhancement with sequentially proactive operation strategies                                                               |2016|Chong Wang                |10.1109/TPWRS.2016.2622858 |N                     |During-event (Resilience-oriented operation)|Proactive-operation strategies                                                                              |Transmission|IEEE 30-bus system, IEEE 118-bus sytem, Guangadong Power Grid|For each t a the faulted lines are sampled                                                                                                                                                                                                                                                                                                                                                                                                              |24                 |Very Large                  |10                       |Typhoon, Windstorm|transformers, transmission lines                                                       |Sequential Mixed Linear Integer Programming to minime Loss of Load at the event unfolding                                                                                                                                                                       |-                                                              |-                     |DC        |-                                                                                                                                                                                                             |
