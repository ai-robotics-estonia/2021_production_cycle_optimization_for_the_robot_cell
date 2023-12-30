# Production Cycle Optimization for the Robot Cell

## Summary
| Company Name | [Alise Technic OÜ](https://www.alisetechnic.eu) |
| :--- | :--- |
| Development Team Lead Name | [Madis Moor](https://www.etis.ee/CV/Madis_Moor/eng/) |
| Development Team Lead E-mail | [madis.moor@taltech.ee](mailto:madis.moor@taltech.ee) |
| Objectives of the Demonstration Project | Optimise robot cell production cycle for small batch production. |
| Final Report | [Optimization of the production cycle performance in a robot-based workplace.docx.pdf](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/files/13797968/Optimization.of.the.production.cycle.performance.in.a.robot-based.workplace.docx.pdf) |

# Description
## Objectives of the Demonstration Project
*Please describe your project objectives in detail.*

The goal is to produce various products in small batches, with high productivity, high quality, and as efficiently as possible. Different processing methods are used in production. Sheet metal processing is a widespread field in mechanical engineering. Bending, in turn, is a very widely used processing method in mechanical engineering. In the robot-based applications working cycle development has a very important role. The working cycle describes the integration of robots with other equipment in the workplace for fulfilling the production task. Working cycle forms the basis for productivity and describes the manufacturing process. Different robot-based applications have different working cycles. Robot bending is widely used to automate the process. Robot-bending workplace components in the real production environment are presented below.

![image22](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/b49ec83f-a8e3-46f8-bddc-1c2e3598f0df)

Cycle time in the manufacturing industry means the average time in which a unit of measure leaves a production process. By reducing the cycle time, the productivity of automation systems can be significantly increased. The goal function in production is typically to ensure maximum productivity or minimum production cost. For better understanding, it is essential to map the activities inside the overall cycle time. An overview of cycle activities is shown below.

![image20](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/eb143550-0d77-4bc5-849f-ee6ffa1d831e)


## Activities and Results of the Demonstration Project
### Challenge
*Please describe challenge addressed (i.e, whether and how the initial challenge was changed during the project, for which investment the demonstration project was provided).*

The performance improvement is a complex engineering task, which consists of several subtasks, which solving lies on recursive multicriteria optimization with the help of AI technologies. The developed methodology is universal and could be implemented also in other kinds of robot cells. Robot-cell performance improvement subtasks are represented below.

![image21](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/0c94d96d-65e1-4c06-9787-1f261da3d27f)


### Data Sources
*Please describe which data was used for the technological solution.*  

The Internet of Things (IoT), which connects the physical environment to cyberspace, has found widespread use today to collect data from the physical world in real-time. This architecture allows us to detect, identify and operate through various electronic components distributed in the environment and connected to the network, resulting in a cyber-physical infrastructure.
This combination allows us to integrate the company's enterprise resource planning (ERP) systems, warehousing systems, and production equipment into a single management system that allows them to automatically exchange data with each other.

Dimusa is a model-based, real-time production monitoring and prediction system with optimal functionality (with custom reconfiguration options) with low investment cost and integration time. The production process analyzation model provides the opportunity to accelerate its application time, together with Key Point Indicator (KPI) specification and the integration of system procedures. The main application area is Small and Medium-sized Enterprises (SME-s), in the field of mechanical and machinery engineering, also the wood and furniture industry. Advanced production monitoring and prediction system are capable of identifying variables affecting performance, such as measuring and monitoring events and situations that directly affect the reliability of production systems and processes. An efficient real-time information flow includes data collection in the system:
- the condition of the equipment,
- production data,
- order fulfillment,
- material flow,
- product quality,
- process data,
- error sequence and reason.
The information listed above is essential for making justified and optimal decisions that ensure more efficiency: production planning, use of resources, maintenance of equipment, and planning of it.

![image28](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/3f564f73-3065-4800-bced-31ebe7b79cca)

The Dimusa data monitoring and collecting system was integrated into Alise Technic robot-based workplace number 117 on the 3rd of March 2022. The monitoring period is set till the end of the demonstration project which is the 30th of June 2022. The sensors were installed on a CNC bending machine (Amada HFBO 50-20), which is described as a productive unit, and to the industrial robot (Motoman MRC SK-16), which is described as an operative unit in a robot-based workplace. The quality of monitored data, for example, occurrence of errors and machine stops are reported by the responsible operator who observes the robot-based work cell. If the reason is unknown, it is complicated to offer a result with a decision algorithm. 
Overall, the system measures 5 KPI parameters (5): 
- Overall Equipment Effectiveness (OEE) which is a standard form of measuring manufacturing productivity.
- Availability which considers unplanned and planned stops,
- Performance which considers slow cycles and small stops,
- Quality which considers defects,
- Speed which indicates time per one piece (throughput).

![image29](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/c3f7df8c-78de-4a15-8969-2dca75b4462f)

### AI Technologies
*Please describe and justify the use of selected AI technologies.*

For daily use, Dimusa provides convenient access to live data for a responsible engineer. All data is collected to a cloud-based server and is visible later, if necessary. In terms of the AI & Robotics Estonia demonstration project, Dimusa system provides us the opportunity to harvest live data and use it as essential input data for running digital Twin simulations for raising the efficiency of the current order or batch. AI-based Digital Twin technology one of the biggest advantages is to work parallelly. Without creating planned stops for our manufacturing workplace, it is possible to optimize the current working cycle, based on live information from production and transferred automatically to the simulation model.

The production and process data which is measured and collected in the previous paragraph (Data collection using Dimusa system), is momentous information input for running simulations with different scenarios. For Alise Technic OÜ demonstration project, a virtual robot-based workplace model was created, using Visual Components software. It is a tailor-made digital environment and describes the physical manufacturing unit identically below.

![image8](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/667a1a2a-cd26-4450-b050-85c84f68de7a)


### Technological Results
*Please describe the results of testing and validating the technological solution.*

The virtual model of a production cell is a computer-based modelling and simulation of a real production environment that can be represented as a digital twin of a particular physical system. It helps to design, plan, analyse and optimize the production processes and activities. In the virtual model, it is essential to present the behaviour of a real production system in a realistic and equally dynamic way by using physical cell data and appropriate KPIs. 
One of the greatest advantages of simulation is to animate a system's behaviour with time. As manufacturing simulation, a way to analyse and experiment production processes in a virtual setting which leads to reducing the time and cost requirements associated with physical testing. Moreover, it assesses inventory, assembly, transportation, and production within a simulation model, resulting information helps to improve target KPIs. However, the 3D simulation and visualization are more promising to fulfil such objectives and one possibility is to use Industrial Virtual Reality (IVR) based 3D visualizations, which can be fixed to obtainable 3D assembly layouts, 3D product models, and process flows generated from simulation models. 
Following is the virtual simulation model of a robotic bending cell created in a 3D environment as shown above, which is a digital replica of the physical cell. The bending cell AS-IS activities were observed in the real environment, layout was mapped, resources and buffers were identified that are executing the whole bending process of sheet metal. Based on that information a process flow was constructed (see below), where each activity and corresponding resource are marked. The process starts with the picking of a blank sheet metal by a robotic arm, positioning of the blank at positioning table, followed by loading of blank in the bending machine, then bending activity, unloading of bended part, and placing the bended part in the pallet by industrial robot as a finished good. Subsequently, the process flow helps to create the 3D simulation model, where the analysis was conducted, and knowledge was captured for the improvement in the throughput of the bending cell.

![image7](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/74de4ad9-4d69-4281-a0df-aa74242566ac)

#### Throughput Analysis by Simulation
Throughput can be defined as the number of parts passing through the process per unit time. In this bending cell, the throughput is the bended parts collected on average in the pallet as finished products for a certain time period. It can be formulated as:

Average Inventory I=Throughput R× Average Flow Time (T)

R=I/T

Here, 
- I – is bended parts produced, 
- T – is the total process time, 
- R – is the throughput of the cell. 

There were two scenarios observed (a) AS-IS with the activity of a repositioning table and (b) TO-BE without the activity of repositioning table. The simulation executed for 1 hour and data about the number of bent parts produced were collected for both scenarios. The analysis of throughput and utilization of the robot is summarized below.

| Scenario 1: with repositioning table | Scenario 2: without repositioning table |
| :--- | :--- |
| ![image9](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/67cf8385-ca64-4511-83db-57998541ebcf) | ![image18](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/401c8231-6bc5-4f5d-8623-b624762f2c2c) |
| ![image3](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/b387a69d-4b87-4381-b170-bc8f7cb1a3c0) | ![image4](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/409a6d7a-2c43-447a-8f66-635a27523aa5) |
| ![image5](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/db5fc98f-1ce3-45bc-bcd6-08a2d0ca5bab) | ![image6](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/38e1674c-7131-4694-9b14-7389635e3088) |
| Throughput = 170 parts/hour | Throughput = 209 parts/hour |
| Utilization of robot = 66 % | Utilization of robot = 64 % |

The removal of repositioning activity from the process leads to improvement in the productivity of the bending cell. The repositioning activity is redundant because the picking of parts from the table by robot is positioned correctly, so there is no need for extra activity and robot motion. The analysis that is conducted through digital model and 3D simulation of the bending cell shows the fixing of layout and eliminating of non-value-added activity helps to increase the throughput by 19%. Hence the application of digital twin facilitates to validate and test the change and its adoption with high assurance. 

### Technical Architecture
*Please describe the technical architecture (e.g, presented graphically, where the technical solution integration with the existing system can also be seen).*

Current robot-bending cell 117 (left) at Alise Technic OÜ

![image19](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/e8019157-43fa-4972-8d9d-09eef36e5689)

Possible rearranged work cell (right)

![image17](https://github.com/ai-robotics-estonia/production_cycle_optimization_for_the_robot_cell/assets/15941300/4e843683-c750-40b0-901f-332871d09d05)

### Future Potential of the Technical Solution
*Please describe the potential areas for future use of the technical solution.*

In future, this virtual model of robot bending cell can be used for different other scenarios’ testing such as related to layout changes, integrating more data collection points, motion study of robot and machining (bending) cycles. It would help not only to analyze the further performance of the cell and subsequently suggestions to improve the effectiveness in the form of OEE of the cell, also the 3D simulation analysis can be a useful input to the AI model and connected to its feedback thread.
