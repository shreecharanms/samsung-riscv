# INSTRUCTION SETS

![image](https://github.com/user-attachments/assets/e6d8c66b-1e0c-4188-aecc-55b1d2d79b5f)



1. **Instruction: auipc a0,0x1d** <br>

![image](https://github.com/user-attachments/assets/6d8175fa-888d-4f76-9f76-edff8ad4d71c)



Instruction - _00000000000000011101|01010|0010111_ <br>
Type - U<br>
Opcode - 0010111<br>
Immediate - 000000000000001110101010<br>
Source Register - None<br>
Destination Register - 01010<br>

2. **Instruction : addw a5,a4,s1**<br>

![image](https://github.com/user-attachments/assets/7cb8f6ee-15f9-4260-9ee6-52aec9bbc198)


Instruction - _0000000|01001|01110|000|01111|0111011_<br>
Type - R<br>
Opcode - 0111011<br>
funct3 - 000 <br>
funct7 - 0000000<br>
Source Register(a5,a4) - 01001,01110<br>
Destination Register(s1) - 01111<br>

3. **Instruction : addi s0,s0,8**<br>
   
![image](https://github.com/user-attachments/assets/f166af4e-efb6-4514-882f-35c85aa84168)

Instruction - 000000001000|01000|000|01000|0010011<br>
Type - I<br>
Immediate - 000000001000<br>
Opcode - 0010011<br>
funct3 - 000 <br>
funct7 - 0000000<br>
Source Register(s0) - 01000<br>
Destination Register(s0) - 01000<br>

4. **Instruction : jalr a5**<br>

![image](https://github.com/user-attachments/assets/8b75bde3-cc27-486c-8126-797550e70deb)

Instruction - 0|0000000000|0|01111000|00001|1100111<br>
Type - J<br>
Immediates - 01111000,0000000000<br>
Opcode - 1100111<br>
Destination Register(a5) - 00001<br>




