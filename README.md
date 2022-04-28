# Full-Datapath
Performs the following operations using RISC-V instruction set:

addi x3, x0, 15
addi x4, x0, 7

add  x5, x3, x4

sw   x5, 100(x0)

lw   x3, 93(x4)

beq  x3,x5,0
