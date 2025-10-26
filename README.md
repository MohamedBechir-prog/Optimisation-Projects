# Unit Commitment Problem

In this project, I will incrementally implement a unit commitment problem using Gurobi. The goal is to meet the projected electricity demand at each time interval by optimally dispatching various types of power plants.

The time horizon spans a single day, divided into five periods to reflect typical fluctuations in electrical load throughout the day.

| Time Period | Demand (MW) |
| --- | --- |
| 12 pm to 6 am | 15000 |
| 6 am to 9 am | 30000 |
| 9 am to 3 pm | 25000 |
| 3 pm to 6 pm | 40000 |
| 6 pm to 12 pm | 27000 |

The dataset includes three types of conventional power plants, each characterized by its minimum and maximum power output, the number of units available, and generation costs.


| Type | Available Units | Minimum output (MW) | Maximum output (MW) | Generation cost (€/MWh) |
| --- | --- | --- | --- | --- |
| 1 | 12 |  850 | 2000 |1.5 |
| 2 | 10 | 1250 | 1750 |1.38 |
| 3 | 5 | 1500 | 4000 |2.35 |

The complexity of the model will gradually increase as the script progresses.

This project is part of the Optimization coursework from my master's program in Energy Systems Optimization at Mines Paris.

The example can also be found in the fifth edition of **Model Building in Mathematical Programming by H. Paul Williams on pages 271-272 and 326-327**.
