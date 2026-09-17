# EXP-3-CHARACTERISTICS-STUDY-OF-METAL-OXIDE-SEMICONDUCTOR-FIELD-EFFECT-TRANSISTOR-MOSFET-
1. AIM
To simulate the drain and transfer characteristics of a MOSFET using LTspice software and to determine its drain resistance and transconductance.
2. APPARATUS / SOFTWARE REQUIRED
•	PC/Laptop
•	LTspice simulation software
•	MOSFET device/model
•	DC voltage sources
•	Voltage/current probes
3. THEORY
3.1 Transfer Characteristics
In MOSFET applications, the input signal is the gate-to-source voltage VGS and the output is the drain current ID. The ability of a MOSFET to amplify the signal is given by the output/input ratio called transconductance.
Transconductance:
gm = dID / dVGS    (with VDS kept constant)
The transfer characteristic represents the relationship between ID and VGS for a constant VDS.
3.2 Drain Characteristics
A MOSFET operates in three regions:
1.	Cut-off region
2.	Linear/Ohmic region
3.	Saturation region
Cut-off Region: The MOSFET is in cut-off when VGS < VT. The drain current is approximately zero.
Linear Region: The MOSFET operates in the linear region when VGS > VT and VDS < (VGS − VT).
Saturation Region: The MOSFET operates in saturation when VGS > VT and VDS ≥ (VGS − VT).
Drain resistance is obtained from the slope of the drain characteristic:
rd = dVDS / dID    (with VGS kept constant)
4. CIRCUIT DIAGRAM
A. Transfer Characteristics – Connect the MOSFET circuit in LTspice. VGS is varied while maintaining a constant VDS, and the corresponding ID is observed.
[Insert LTspice Transfer Characteristics Circuit Diagram Here]
B. Drain Characteristics – Connect the MOSFET circuit in LTspice. VDS is varied for different constant values of VGS, and the corresponding ID is observed.
[Insert LTspice Drain Characteristics Circuit Diagram Here]
5. PROCEDURE
A. Transfer Characteristics
4.	Connect the MOSFET circuit as per the circuit diagram in LTspice.
5.	Set the required VGS and VDS values.
6.	Set the required DC sweep parameters and secondary values.
7.	Place the voltage/current probe at the required terminal of the MOSFET.
8.	Run the simulation.
9.	Observe and plot the relationship between ID and VGS.
10.	Determine the transconductance gm from the slope of the transfer characteristic.
B. Drain Characteristics
11.	Connect the MOSFET circuit as per the circuit diagram in LTspice.
12.	Set the required VGS and VDS values.
13.	Set the required DC sweep parameters and secondary sweep values.
14.	Place the voltage/current probe at the required terminal of the MOSFET.
15.	Run the simulation.
16.	Observe and plot the relationship between ID and VDS for different values of VGS.
17.	Identify the cut-off, linear and saturation regions.
18.	Determine the drain resistance rd from the slope of the drain characteristic.
6. OBSERVATION
A. Transfer Characteristics
S. No.	VGS (V)	VDS (V)	ID (mA)
1			
2			
3			
4			
5			
6			
7			
8			
Graph: Plot ID vs. VGS for constant VDS.
B. Drain Characteristics
S. No.	VDS (V)	VGS (V)	ID (mA)
1			
2			
3			
4			
5			
6			
7			
8			
Repeat the observation for different constant values of VGS.
Simulation Results

 ID vs. VDS for different values of VGS.



8. CALCULATIONS
Transconductance:
gm = ΔID / ΔVGS
Therefore,  gm = __________________ S
Drain Resistance:
rd = ΔVDS / ΔID
Therefore,  rd = __________________ Ω
<img width="1032" height="693" alt="Screenshot 2026-09-08 134217" src="https://github.com/user-attachments/assets/0ae82612-59bd-4e8e-803e-bd0b71e75a1c" />

10. RESULT
Thus, the drain and transfer characteristics of the MOSFET were simulated using LTspice. The values of transconductance (gm) and drain resistance (rd) were determined from the respective characteristics.
gm = __________________ S
rd = __________________ Ω
11. PRECAUTIONS
•	Check the MOSFET terminal connections before starting the simulation.
•	Use appropriate voltage sweep limits.
•	Keep VDS constant while obtaining transfer characteristics.
•	Keep VGS constant for each drain-characteristic curve.
