# EE568 Project-4

## PM Motor Comparison Analysis

## Deadline 28/06 23:59

In this assignment you are going to design and analyze different electrical machines. The technical details of the machines will be sent you personally by email. Although the machine types are different, this is a general guide about the content of your project.

All rules regarding the report format, Github repo and number of commits still hold **(10pts)**. Please do your own work. You need to submit a PDF report summarizing all the works you did, please discuss any important points and state any assumptions you make. Reports that give just the analysis and FEA results without enough discussion and comments get a low grade.

### Literature Review **(15pts)**

In this section, I expect you to summarize the current status of the literature on your machine topology. Please read and summarize journal papers relevant to your machine topology. Please cite at least 5-6 recent SCI journals, discuss and synthesize them properly. 

- https://www.scribbr.com/dissertation/literature-review/
- https://writingcenter.unc.edu/tips-and-tools/literature-reviews/

### Analytical Calculation & Sizing **(25pts)**

In this part, please discuss the relevant analytical calculations, and give the details for the rough sizing of the machine. These can be listed as (but not limited to):

- Choose a specific machine constant by choosing the magnetic and electrical loading. **(4pts)**
- Define the rough dimensions (airgap clearance, rotor diameter, axial length) **(4pts)**
- Choose the winding configurations (number of slots, number of coils, cable size etc.) **(4pts)**
- Calculate the other parameters such as the teeth/slot dimensions, back-core thickness etc.**(4pts)**
- Material selection (laminations, magnet grade etc.)**(4pts)**
- Electrical circuit parameter estimations (induced voltage, flux per pole, phase resistance, phase inductance etc.)**(4pts)**


### FEA Modelling **(30pts)**

Model your analytical design using a FEA software. 2D analyses should be fine, but for some topologies 3D FEA analysis may be required. If this is the case, you may simplify the model by using rotational symmetry or linear materials etc.

In this part, please include at least the following:

- Air-gap flux density distribution **(5pts)**
- Flux density distribution in the critical parts such as back-core, stator teeth etc. **(5pts)**
- Phase resistance (in the 2D FEA calculations you need to include the end-winding) **(5pts)**
- Phase inductance (if our machine has saliency please calculate d-axis and q-axis inductances separately) **(5pts)**
- Induced phase voltage (you don't have to make a transient analysis, but use magneto-static analysis to calculate the flux per-pole at various rotor positions and approximate the induced phase voltage) **(5pts)**
- Efficiency calculation at rated load and half-load (please include the temperature effects, core losses etc.) **(5pts)**

### Comparison & Discussion **(20pts)**

In this stage, if you see any unfeasible designs please go back to the analytical model and modify your design. I expect to be many iterations, please reflect these in the report **(4pts)**. Compare the analytical and FEA models clearly and discuss any discrepancies **(4pts)**. 

If you tried a few different designs, such as with different pole number, magnet grade, rotor diameter etc, please give a comparison between these designs, and summarize how you come up with the final design.

Also in this part, please give main mechanical parameters of the machine:

- Outer Diameter, axial length, aspect ratio 
- Material mass (iron, copper, magnet) **(4pts)**
- Torque density, power density **(4pts)**

It is also expected to have some kind of evaluation of your design with the similar designs in the literature **(4pts)**. Please discuss your strong and weak points objectively.

