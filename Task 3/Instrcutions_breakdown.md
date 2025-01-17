# INSTRUCTION SETS

![image](https://github.com/user-attachments/assets/e6d8c66b-1e0c-4188-aecc-55b1d2d79b5f)

1. **Instruction: auipc a0,0x1d** <br>

![image](https://github.com/user-attachments/assets/6d8175fa-888d-4f76-9f76-edff8ad4d71c)



Instruction - _00000000000000011101|01010|0010111_ <br>
Type - U
Opcode - 0010111
Immediate - 000000000000001110101010
Source Register - None
Destination Register - 01010

2. **Instruction : addw a5,a4,s1**

![image](https://github.com/user-attachments/assets/7cb8f6ee-15f9-4260-9ee6-52aec9bbc198)


Instruction - _0000000|01001|01110|000|01111|0111011_
Type - R
Opcode - 0111011
funct3 - 000 
funct7 - 0000000
Source Register(a5,a4) - 01001,01110
Destination Register(s1) - 01111

3. **Instruction : addi s0,s0,8**
   
![image](https://github.com/user-attachments/assets/f166af4e-efb6-4514-882f-35c85aa84168)

Instruction - 000000001000|01000|000|01000|0010011
Type - I
Immediate - 000000001000
Opcode - 0010011
funct3 - 000 
funct7 - 0000000
Source Register(s0) - 01000
Destination Register(s0) - 01000

4. **Instruction : jalr a5**

![image](https://github.com/user-attachments/assets/8b75bde3-cc27-486c-8126-797550e70deb)

Instruction - 0|0000000000|0|01111000|00001|1100111
Type - J
Immediates - 01111000,0000000000
Opcode - 1100111
Destination Register(a5) - 00001




