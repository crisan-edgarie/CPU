# CPU after modifed Harvard arhitecture 
# Has 16 instructions on 3 operands --> RISC arhitecture
# Has 16 registers with 8 bits each
# Made to be run on FPGA
# Instruction structure:
# |31    28|27  24|  23 |22     17|  16 |15  12|11 8|7   0|
# |  cond  | 0000 |  I  | op_code |  S  |  Rd  | Rs | Op2 |
