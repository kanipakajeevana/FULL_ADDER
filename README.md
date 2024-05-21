# AIM
To simulate and synthesis half adder using vivado.
# APPARTUS REQUIRE
vivado 2023.2 software.
# PROCEDURE
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.
# Truth Table
![image](https://github.com/kanipakajeevana/FULL_ADDER/assets/170450203/08ecf505-0c7c-4b3a-8e64-39669bdb341e)


# Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/418e00aa-ed19-4ab3-a413-bae9575bff0e)
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/0c26fe47-d78c-43dd-ac0d-804e42
Sum = A XOR B


Carry = A AND B
# VERILOG CODE
module Half_adder(a,b,sum,carry);

input a,b;

output sum,carry;

xor g1(sum,a,b);

and g2(carry,a,b);

endmodule

# OUTPUT
![image](https://github.com/kanipakajeevana/FULL_ADDER/assets/170450203/ec46c684-5b37-40d7-8f87-78848dc6bd1a)

# RESULT
Thus the verilog program for half adder has been simulated and verified successfully.


