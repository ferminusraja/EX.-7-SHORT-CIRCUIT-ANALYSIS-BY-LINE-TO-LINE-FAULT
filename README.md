# EX.-7-SHORT-CIRCUIT-ANALYSIS-BY-LINE-TO-LINE-FAULT
# AIM: 
To find unsymmetrical short circuit parameters for the given system for line to line fault by using 
ETAP software. 
# THEORY: 
When an abnormal condition arises in a power system such asfault, an insulation flashover or 
lightning stroke to the transmission tower, high current flows in the power system. These currents are 
sensed to the relays to isolate the faulty section of the power system. Delay in the operation of the circuit 
breakers might result in creating instability in the system and also cause burnout of costly equipment such 
as transformer, generator, etc. 
Short circuit study is an important study which provides vital information regarding the 
magnitude of fault current through various components of the power system during short circuit. This 
helps in the proper selection of the circuit breakers and relays. It also helps in relay co-ordination. 
In arriving at a mathematical model for short circuit studies, a number of assumptions are made 
which simplify the formulation of the problem. Certain valid assumptions are: 
1. The load, line charging capacitances and other shunt connections to the ground are neglected. 
2. The generator is represented by a voltage source in series with a reactance which is taken to be 
sub-transient or transient reactance. 
3. All the transformers are considered to be at their nominal taps. 
4. If the resistance of the transmission lines is sufficiently smaller than the reactance the resistances are 
neglected. 
5. Pre-fault voltage at all the buses is (1+j0) p.u. 
6. The mathematical model of the system can be derived as follows.
# ALGORITHM: 
1. Start the execution. 
2. Read the given data and form the sequence impedance matrix. 
3. Let I o=0 and find fault current I 1= (E)/ (Zkk1+Z 2+I ) and I 2=-I. 
4. Find fault MVA for the specified bus and print the calculated value. 
5. Stop the execution.
# CIRCUIT DIAGRAM:
<img width="171" height="413" alt="image" src="https://github.com/user-attachments/assets/1f03539f-fcbf-4e7f-a10a-e973e91a42fb" />

# OUTPUT:
<img width="922" height="393" alt="image" src="https://github.com/user-attachments/assets/7c13a9f8-b547-4aeb-9e37-3525e73b7eb0" />

# RESULT:
Thus short circuit analysis by line to line fault is performed in etap software and the output is verified.
