# INSTRUCTION SETS

![image](https://github.com/user-attachments/assets/e6d8c66b-1e0c-4188-aecc-55b1d2d79b5f)

<br>
<br>
<br>

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

5. **Instruction sd s1, 8(sp)**<br>
   
 ![image](https://github.com/user-attachments/assets/4d6e1291-1fe6-4cc8-84e0-e5f7ff9a20f3)


Instruction - 00000000100|10001|00110|100|01000|0100011<br>
Type - S<br>
Immediate - 00000000100<br>
Opcode - 0100011<br>
Source Registers(s1,sp) - 10001,00110
func3 - 100
Destination Register(a5) - 00001<br>

6. **Instrction : sub a2,a2,a0**

![image](https://github.com/user-attachments/assets/84cdc49e-63ab-43d8-bdfc-48b472c85155)

Instruction - _0100000|01010|01100|000|01100|0110011_<br>
Type - R<br>
Opcode - 0110011<br>
funct3 - 000 <br>
funct7 - 0100000<br>
Source Register(a2,a2) - 01010,01100<br>
Destination Register(a0) - 01100<br>

7. **Insreuction : subw a5,a5,a4**

![image](https://github.com/user-attachments/assets/30678f55-6c2a-472d-97a4-accdba725d9b)

Instruction - _0100000|01110|01111|000|01111|0111011_<br>
Type - R<br>
Opcode - 0111011<br>
funct3 - 000 <br>
funct7 - 0100000<br>
Source Register(a5,a5) - 01110,01111<br>
Destination Register(a4) - 01111<br>

8. **Instruction : and a3,a2,a3

![image](https://github.com/user-attachments/assets/da566a57-4314-4621-ae59-1a5036de7e1c)

Instruction - _0000000|01101|01100|111|01101|0110011_<br>
Type - R<br>
Opcode - 0110011<br>
funct3 - 000 <br>
funct7 - 0000000<br>
Source Register(a3,a2) - 01101,01100<br>
Destination Register(a3) - 01101<br>

9. **Instruction : lui a5, 0x2

![image](https://github.com/user-attachments/assets/d27877f1-8bb4-4220-b401-ff91821c8d55)


Instruction - 0|0000000000|0|00000010|01111|0110111<br>
Type - I<br>
Immediates - 00000010,0000000000<br>
Opcode - 0110111<br>
Destination Register(a5) - 01111<br>

10. **Instruction : or a3,a5,a3

![image](https://github.com/user-attachments/assets/12341b0c-c081-47af-af66-c3e77efae671)

Instruction - _0000000|01111|01101|110|01111|0110011_<br>
Type - R<br>
Opcode - 0110011<br>
funct3 - 110 <br>
funct7 - 0000000<br>
Source Register(a3,a5) - 01111,01101<br>
Destination Register(a3) - 01111<br>


