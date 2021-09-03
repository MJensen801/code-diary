## MIPS Cheat Sheet

#### R-Type (Registers)
**Math**\n
add $1, $2, $3\t $1 = $2 + $3\n
sub $1, $2, $3\t $1 = $2 - $3\n
mult $1, $2, $3\t $1 = $2 x $3\n
div $1, $2, $3\t $1 = $2 / $3

**Bitwise**\n
and $1, $2, $3\t $1 = $2 AND $3\n
or $1, $2, $3\t $1 = $2 OR $3\n
xor $1, $2, $3\t $1 = $2 XOR $3\n
nor $1, $2, $3\t $1 = $2 NOR $3

**Shifting**\n
sll $1, $2, shamt\t $1 = $2 << shamt (shift left logical)\n
srl $1, $2, shamt\t $1 = $2 >> shamt (shift right logical)

#### I-Type (Immediate)
**Branching**\n
beq $1, $2, imm\t if ($1 = $2) branch to imm\n
bne $1, $2, imm\t if ($1 != $2) branch to imm\n
blez $1, $2, imm\t if ($1 <= $2) branch to imm\n
bgtz $1, $2, imm\t if ($1 >= $2) branch to imm

**Math**\n
addi $1, $2, imm\t $1 = $2 + imm

**Bitwise**\n
andi $1, $2, imm\t $1 = $2 AND imm\n
ori $1, $2, imm\t $1 = $2 OR imm\n
xori $1, $2, imm\t $1 = $2 XOR imm

#### J-Type (Jump)
j address\t (jump to address)\n
jal address\t (jump to address but save my current location)
