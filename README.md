## รายงานวิชา สถาปัตยกรรมคอมพิวเตอร์

### สรุปเนื้อหา
#### MIPS Instruction Format 
*      คำสั่งของ MIPS จะมีทั้งหมด 3 รูปแบบ โดยเเต่ละรูปแบบจะมีขนาด 32 bit ประกอบด้วย R-format , I-format , J-format 

<br>**R-format**

|op     |rs     |rt     |rd     |shamt  |func   |
| ----- | ----- | ----- | ----- | ----- | ----- |
|6 bit  |5 bit  |5 bit  |5 bit  |5 bit  |6 bit  |

<br>**I-format**

|op     |rs     |rt     |offset     |
| ----- | ----- | ----- | -----     | 
|6 bit  |5 bit  |5 bit  |16 bit     |

<br>**J-format**

|op     |address |
| ----- | -----  | 
|6 bit  |26 bit  |



