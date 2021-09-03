## MIPS Cheat Sheet

#### R-Type (Registers)
**Math**
add $1, $2, $3\t $1 = $2 + $3

sub $1, $2, $3\t $1 = $2 - $3

mult $1, $2, $3\t $1 = $2 x $3

div $1, $2, $3\t $1 = $2 / $3

**Bitwise**
and $1, $2, $3\t $1 = $2 AND $3

or $1, $2, $3\t $1 = $2 OR $3

xor $1, $2, $3\t $1 = $2 XOR $3

nor $1, $2, $3\t $1 = $2 NOR $3

**Shifting**
sll $1, $2, shamt\t $1 = $2 << shamt (shift left logical)

srl $1, $2, shamt\t $1 = $2 >> shamt (shift right logical)

#### I-Type (Immediate)
**Branching**
beq $1, $2, imm\t if ($1 = $2) branch to imm

bne $1, $2, imm\t if ($1 != $2) branch to imm

blez $1, $2, imm\t if ($1 <= $2) branch to imm

bgtz $1, $2, imm\t if ($1 >= $2) branch to imm

**Math**
addi $1, $2, imm\t $1 = $2 + imm

**Bitwise**
andi $1, $2, imm\t $1 = $2 AND imm

ori $1, $2, imm\t $1 = $2 OR imm

xori $1, $2, imm\t $1 = $2 XOR imm

#### J-Type (Jump)
j address\t (jump to address)

jal address\t (jump to address but save my current location)
